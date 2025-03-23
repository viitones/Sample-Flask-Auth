# Sample Flask Auth

Bem-vindo ao projeto **Sample Flask Auth**! Este sistema é uma aplicação web simples que demonstra a implementação de autenticação usando Flask.

## O que o sistema faz

Este sistema permite que os usuários se registrem, façam login e acessem páginas protegidas. Ele inclui funcionalidades básicas de autenticação e gerenciamento de sessões.

## Funcionalidades

- **Registro de Usuário**: Permite que novos usuários se registrem com um nome de usuário e senha.
- **Login de Usuário**: Usuários registrados podem fazer login usando suas credenciais.
- **Logout de Usuário**: Usuários autenticados podem fazer logout para encerrar a sessão.
- **Atualização de Dados**: Usuários autenticados podem atualizar sua própria senha, somente admin pode atualizar qualquer senha.
- **Deleção de Usuários**: Usuários admin pode deletar qualquer usuário.
- **Páginas Protegidas**: Acesso a páginas específicas é restrito a usuários autenticados e admin.
- **Mensagens Flash**: Feedback visual para ações de registro, login e logout.

## Tecnologias Usadas

- **Python**: Linguagem de programação principal.
- **Flask**: Micro framework web para Python.
- **Flask-SQLAlchemy**: Extensão que facilita a integração do SQLAlchemy com Flask, permitindo a utilização de bancos de dados relacionais de forma simples e eficiente.
- **Flask-Login**: Extensão para gerenciar sessões de usuário.
- **Werkzeug**: Biblioteca WSGI para manipulação de senhas e segurança.
- **PyMySQL**: Interface para conectar ao banco de dados MySQL.
- **Cryptography**: Biblioteca para criptografia e segurança.
- **bcrypt**: Biblioteca para hashing de senhas.

## Como Executar

1. Clone o repositório:
  ```bash
  git clone https://github.com/viitones/sample-flask-auth.git
  ```
2. Navegue até o diretório do projeto:
  ```bash
  cd sample-flask-auth
  ```
3. Crie um ambiente virtual:
  ```bash
  python -m venv venv
  ```
4. Ative o ambiente virtual:
  - No Windows:
    ```bash
    venv\Scripts\activate
    ```
  - No Linux/Mac:
    ```bash
    source venv/bin/activate
    ```
5. Instale as dependências:
  ```bash
  pip install -r requirements.txt
  ```
6. Execute a aplicação:
  ```bash
  flask run
  ```

## Como Usar na Sua Máquina

1. Use o Postman ou Insomnia para ter acesso às rotas
2. Registre um novo usuário.
3. Faça login com o usuário registrado.
4. Navegue pelas páginas protegidas.

---

Feito com ❤️ por Victor
