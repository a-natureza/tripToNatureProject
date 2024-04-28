# TripNature Project

a project for students of Floripa Mais Tech's FuturoDev course students to put in practice concepts learned in class.

# Local Repository Setup

Fork project on github

clone to your machine

add remote upstream

create postgres database

setup your .env

### Na primeira vez é necessário instalar as dependencias:

1. `npm install`
2. `cp .env_example .env`

## Trabalhando com migrations:

### Criar uma migration

1. `sequelize migration:generate --name alter_table_adicionar_login_alunos`
2. `npx sequelize-cli migration:generate --name criar_tabela_produtos`

### Rodar uma migration. Opções:

1. Opção nº 1: `sequelize db:migrate`
2. Opção nº 2: `npx sequelize db:migrate`

### Reverter a última migration:

1. `sequelize-cli db:migrate:undo`
2. `npx sequelize-cli db:migrate:undo`

## Documentação do Sequelize:

https://sequelize.org/docs/v6/core-concepts/model-basics/

## Novas Bibliotecas utilizadas:

### instalar o sequelize

`npm install sequelize`

### instalar o driver do PostgreSQL

`npm install pg`

### instalar o CLI do sequelize

`npm install -g sequelize-cli`

### instalar o dotenv

`npm install dotenv`

### instalar o JsonWebToken ( JWT )

`npm install jsonwebtoken`

### instalar o bcryptjs

`npm install bcryptjs`
