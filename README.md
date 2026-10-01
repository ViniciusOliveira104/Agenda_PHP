# New Agenda 2.0

Sistema de gerenciamento de usuários e contatos desenvolvido em PHP, utilizando MySQL para armazenamento dos dados e AdminLTE para a interface.

## Sobre o projeto

O New Agenda 2.0 é uma aplicação web criada para facilitar o cadastro e gerenciamento de usuários e contatos.

O sistema permite realizar operações como cadastro de usuários, cadastro de contatos, edição de informações, gerenciamento de perfil e visualização de relatórios.

## Funcionalidades

- Cadastro de usuários
- Login de usuários
- Cadastro de contatos
- Edição de contatos
- Exclusão de contatos
- Perfil do usuário
- Relatórios
- Upload de foto do usuário
- Validação de formatos de imagem
- Senhas armazenadas com hash
- Conexão com banco de dados MySQL usando PDO
- Interface baseada no AdminLTE

## Tecnologias utilizadas

- PHP
- MySQL
- PDO
- HTML5
- CSS3
- JavaScript
- AdminLTE
- Bootstrap
- Font Awesome

## Estrutura do projeto

```text
agendaPHP/
│
├── config/
│   └── conexao.php
│
├── dist/
│   ├── css/
│   ├── js/
│   └── img/
│
├── img/
│   ├── avatar_p/
│   ├── cont/
│   └── user/
│
├── includes/
│   ├── footer.php
│   ├── header.php
│   └── sair.php
│
├── paginas/
│   ├── home.php
│   └── conteudo/
│       ├── cadastro_contato.php
│       ├── perfil.php
│       ├── relatorio.php
│       └── update_contato.php
│
├── plugins/
│
├── cad_user.php
├── index.php
├── new_agenda.sql
├── LICENSE
└── README.md
