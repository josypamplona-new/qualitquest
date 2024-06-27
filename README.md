# Projeto de Backend para App de Pesquisas

## Descrição

O foco desse projeto é mostrar as habilidades backend aprendidas ao longo de dois anos e praticadas até hoje. O objetivo do projeto é desenvolver o backend de um aplicativo de pesquisas em TypeScript, com funcionalidades para dispositivos móveis e desktop.

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
- **Banco de Dados**: [Nome do Banco de Dados, ex MySQL, ]
- **Autenticação**: JWT, OAuth2.0
- **Docker**: Contêineres simultâneos para ambiente de desenvolvimento e produção
- **Outras Ferramentas**: [Ferramentas adicionais, ex: Docker]

## Estrutura do Projeto

```plaintext
src/
├── backend/
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
