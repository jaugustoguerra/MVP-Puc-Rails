Claro, sem problemas. Aqui está uma versão do `README.md` focada exclusivamente na execução local do projeto, sem nenhuma menção ao Docker.

-----

# 🎓 Gerenciador de Alunos (MVP Puc Rio)

Este projeto é uma aplicação web para o gerenciamento de alunos, com uma API RESTful construída em Ruby on Rails e um frontend moderno e interativo em React.

## ✨ Funcionalidades

  * ✅ **Cadastrar Aluno**: Adiciona novos alunos ao banco de dados.
  * 🔍 **Listar Todos os Alunos**: Visualiza todos os alunos cadastrados.
  * 🧾 **Buscar Aluno por CPF**: Procura por um aluno específico usando seu CPF.
  * ❌ **Deletar Aluno**: Remove o registro de um aluno.

## 🛠️ Tecnologias Utilizadas

  * **Backend**: Ruby on Rails (API-only)
  * **Frontend**: React
  * **Banco de Dados**: SQLite

## 🧑‍💻 Guia de Instalação e Execução

Siga os passos abaixo para configurar e executar o projeto em seu ambiente de desenvolvimento local.

### 1\. Pré-requisitos

Antes de começar, certifique-se de que você tem as seguintes ferramentas instaladas:

  * **Ruby**: Versão 3.1.2 ou superior.
  * **Bundler**: Gerenciador de pacotes para Ruby (`gem install bundler`).
  * **Node.js**: Versão 16 ou superior.
  * **NPM** ou **Yarn**: Gerenciador de pacotes para Node.js.

### 2\. Configurando o Backend (Ruby on Rails)

Execute os seguintes comandos a partir da pasta `mvp_backend_rails`.

1.  **Instale as dependências (gems):**
    ```bash
    bundle install
    ```
2.  **Crie e prepare o banco de dados:**
    ```bash
    rails db:create
    rails db:migrate
    ```
3.  **Inicie o servidor Rails na porta 5000:**
    ```bash
    rails server -p 5000
    ```
    A API estará disponível em `http://localhost:5000`.

### 3\. Configurando o Frontend (React)

Em **outro terminal**, execute os seguintes comandos a partir da pasta `mvp-frontend-react`.

1.  **Instale as dependências:**
    ```bash
    npm install
    ```
2.  **Inicie a aplicação React:**
    ```bash
    npm start
    ```
    A aplicação será aberta automaticamente no seu navegador, geralmente em `http://localhost:3000`. Ela se comunicará com o backend que está rodando na porta 5000.

## 📂 Estrutura do Projeto

```
.
├── mvp-frontend-react/     # Aplicação Frontend em React
│   ├── public/
│   ├── src/
│   └── package.json
│
├── mvp_backend_rails/      # API Backend em Ruby on Rails
│   ├── app/
│   ├── config/
│   ├── db/
│   └── Gemfile
│
└── README.md

```
## 🔗 Código Fonte

* **Frontend (React):** [jaugustoguerra/mvp-frontend-react](https://github.com/jaugustoguerra/mvp-frontend-react)
* **Backend (Ruby on Rails):** [jaugustoguerra/mvp_backend_rails](https://github.com/jaugustoguerra/mvp_backend_rails)
