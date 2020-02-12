<h1 align="center">
<br>
  <img src=".github/logo.png" alt="FastFeet" width="300px">
<br>
<br>
FASTFEET
</h1>

<p align="center">FASTFEET é uma aplicação completa (Back-end, Front-end e Mobile) que é avaliada para emissão do Certificado do Bootcamp GoStack da <a href="https://rocketseat.com.br/gostack" 
rel="nofollow">Rocketseat</a>.</p>

<blockquote align="center">“Não espere para plantar, apenas tenha paciência para colher”!</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/wendhio/fastfeet/backend">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/wendhio/fastfeet">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/wendhio/fastfeet">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/wendhio/fastfeet">
  <img alt="GitHub" src="https://img.shields.io/github/license/wendhio/fastfeet">
</p>

## :date: Entregas

- [Etapa1](https://github.com/Rocketseat/bootcamp-gostack-desafio-02) - [ ]
- [Etapa2](https://github.com/Rocketseat/bootcamp-gostack-desafio-03) - [ ]
- [Etapa3](https://github.com/Rocketseat/bootcamp-gostack-desafio-04) - [ ]
- [Etapa4](https://github.com/Rocketseat/bootcamp-gostack-desafio-05) - [ ]

## Features

Esta aplicatição apresenta todas as mais recentes ferramentas e práticas em desenvolvimento!

- ⚛️ [**React Js**](https://pt-br.reactjs.org/) — Uma biblioteca JavaScript para criar interfaces de usuário.
- ⚛️ [**React Native**](https://facebook.github.io/react-native/) — Uma biblioteca que fornece uma maneira de criar aplicativos nativos para Android e iOS.
- 💹 [**Node Js**](https://nodejs.org/en/) — Ambiente de execução Javascript no servidor.
- [Express](https://expressjs.com/)

## Getting started

Para clonar e executar esta aplicação é necessário o [Git](https://git-scm.com/downloads),
[**Node Js**](https://nodejs.org/en/), [PostgreSQL](https://hub.docker.com/_/postgres),
[Yarn](https://classic.yarnpkg.com/en/docs/install#debian-stable) e [Docker](https://docs.docker.com/install/linux/docker-ce/)

Clone o projeto

`$ git clone https://github.com/wendhio/fastfeet.git`

### BackEnd

Execute os seguintes comandos:

```
# Entre no repositório
$ cd backend

# Instale as dependências
$ yarn

# Iniciar conteiner do Docker
$ docker start database

# Inicie o servidor
$ yarn dev

# Executar a migration
$ yarn sequelize db:migrate
```

Para usar a API é necessário o [Insomnia](https://insomnia.rest/) e acessar as rotas:

- POST
- PUT

OBS.: Documentar as rotas com _swagger_....

### Ferramentas de Desenvolvimento

- [Nodemon](https://www.npmjs.com/package/nodemon) - Script de monitor simples para Nodejs
- [Sucrase](https://sucrase.io/) - Para utilizar várias funções do ES6 (ECMAScript 6)
- [ESLint](https://github.com/eslint/eslint) - Lib para identificar erros envolvendo padronização de códigos
- [Prettier](https://github.com/prettier/prettier) - Deixa o código muito mais bonito

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.
