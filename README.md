# json-server-base

Esse é o repositório com a base de JSON-Server + JSON-Server-Auth já configurada, feita para ser usada no desenvolvimento das API's nos Capstones do Q2.

## Endpoints

### Cadastro

POST /users
POST /villains <br/>
POST /sons <br/>

o endpoint (POST /users) serve para cadastrar um personagem de um game, o endpoint (POST /villains) serve para cadastrar o vilão do personagem, o endpoint (POST /sons) serve para cadastrar o filho caso o personagem tenha

### Login

POST /login <br/>
POST /signin

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos personagens cadastrados na lista de "Users"

### Villains

GET /villains <br/>

você precisará logar o personagem para acessar os vilões dele

### Sons

GET /sons <br/>

você precisará logar o personagem para ver os filhos dele
