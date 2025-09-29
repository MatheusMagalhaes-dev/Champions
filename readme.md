# 🏆 Champions API

Uma **API RESTful** inicial desenvolvida para o gerenciamento completo de **Clubes** e **Jogadores**. Este projeto serve como um backend para a criação, leitura, atualização e exclusão de dados (**CRUD**) relacionados a campeonatos e equipes.

## 🚀 Tecnologias Utilizadas

Este projeto foi construído inteiramente no ecossistema Node.js, focado na tipagem forte e segurança do **TypeScript**.

* **Linguagem:** **TypeScript**
* **Runtime:** **Node.js**
* **Framework HTTP:** **Express e Cors**
* **Banco de Dados:** **Totalmente em Cache**

## ✨ Funcionalidades (CRUD)

A API fornece endpoints para o gerenciamento completo das entidades de `Times` e `Jogadores`.

| Entidade | Funcionalidade | Endpoint (Exemplo) | Método |
| :--- | :--- | :--- | :--- |
| **Jogador** | Criar um novo Jogador | `/players` | `POST` |
| **Jogador** | Listar todos os Jogadores | `/players` | `GET` |
| **Jogador** | Listar um Jogador | `/players/{id}` | `GET` |
| **Jogador** | Deletar um Jogador | `/players/{id}` | `DELETE` |
| **Jogador** | Corrigir um Jogador | `/players/{id}` | `PATCH` |


## 🛠️ Como Executar o Projeto

Siga os passos abaixo para configurar e rodar a API em sua máquina local.

### Pré-requisitos

* **Node.js** (Versão LTS recomendada).
* **npm** (Gerenciador de pacotes).

### 1. Clonar o Repositório

```
git clone [https://github.com/MatheusMagalhaes-dev/Champions.git](https://github.com/MatheusMagalhaes-dev/Champions.git)
```
```
cd Champions
```
# 2. Instalar Dependências
```
npm install
```

### 3. Configurar Variáveis de Ambiente
Crie um arquivo chamado .env na raiz do projeto e defina as variáveis de ambiente necessárias para a conexão com o banco de dados e a porta do servidor.


# Variáveis de Conexão com o Banco de Dados
```
PORT=3000
```
```
npm start:watch
```

#### O servidor estará rodando em http://localhost:[PORTA] (por padrão, http://localhost:3000).


# 🤝 Contribuição
Contribuições, sugestões de melhoria ou correções de bugs são sempre bem-vindas!

Faça um Fork do projeto.

Crie uma nova branch (git checkout -b feature/sua-feature).

Faça suas mudanças e commite (git commit -m 'feat: Adiciona nova funcionalidade').

Abra um Pull Request.
