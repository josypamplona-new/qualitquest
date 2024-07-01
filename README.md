# Projeto de Backend para App de Pesquisas

## Descrição

O foco deste projeto é mostrar as habilidades backend aprendidas ao longo de dois anos e praticadas até hoje. O objetivo do projeto é desenvolver o backend de um aplicativo de pesquisas em TypeScript, com funcionalidades para dispositivos móveis e desktop.

## Objetivos

- Desenvolver um backend robusto em TypeScript.
- Criar uma API para gerenciamento de pesquisas com perguntas fechadas e abertas.
- Armazenar respostas e dados básicos de entrevistadores e entrevistados em um banco de dados.

## Funcionalidades

- **Autenticação e Autorização**: Gerenciamento seguro de usuários.
- **CRUD de Pesquisas**: Criação, leitura, atualização e exclusão de pesquisas.
- **Gerenciamento de Respostas**: Armazenamento e recuperação de respostas de pesquisas.
- **Dashboard**: Visualização de dados e estatísticas das pesquisas.

## Tecnologias Utilizadas

- **Linguagem**: TypeScript
- **Framework**: [Nome do Framework, ex: Express, NestJS]
- **Banco de Dados**: [Nome do Banco de Dados, ex: MySQL]
- **Autenticação**: JWT, OAuth2.0
- **Docker**: Contêineres simultâneos para ambiente de desenvolvimento e produção
- **Outras Ferramentas**: [Ferramentas adicionais, ex: Docker]

## Estrutura do Projeto



## Querido Diário
*** O que fiz até agora?***
- IMPLANTEI O FRONT END com React Node (não o desenvolvi).
USEI O COMANDO docker para desenvolver um container para banco de dados:

docker pull mysql:latest

docker run --name qualitquest-db -e MYSQL_ROOT_PASSWORD=123456 -d mysql:latest

- ATRAVÉS DO COMANDO na pasta app/backend/src:


npx sequelize-cli db:seed:all

- Implantei a pasta config, migration, models, seeds.

DENTRO DA RAIZ backend, onde está instalado o Node para backend, usei o comando:


npm install express sequelize sequelize-cli mysql2

- DENTRO DA RAIZ DO PROJET configurei o arquivo com a variavel process com o comando

npm i --save-dev @types/node
-----------------------------------
****REZETEI O PROGETO****
**POR PROBLEAMAS DE CRIAÇÃO DE CONTAINERES RESETEI TUDO TIREI O FRONT E PREOCUPEI SOMENTE EM CRIAR O DB E O BACKEND**
** DENTRO DA PASTA BACKEN INICIEI O NODE**
npm init -y  
instalei dependencias
npm install -D typescript  
npm install --save @nestjs/sequelize sequelize sequelize-typescript mysql2

-DEPOIS 
npm install --save-dev @types/sequelize
npm install @types/express  

-depois 

npm install cpy-cli del-cli --save-dev

-subi os containers simultaneos 

docker compose up

```plaintext
app/    
├── backend/src
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── services
│   └── utils
├── tests
│   ├── unit
│   └── integration
├── .env.example
├── docker-compose.yml
├── Dockerfile
├── package.json
├── tsconfig.json
└── README.md