# 🧑‍🚀 In.orbit (BackEnd)

![in.orbit](./src/assets/imageToReadmeBackEnd.png)

## 📃 Descrição

Este projeto é um site para gerenciamento de metas semanais. Com ele, você pode:
- Criar metas semanais personalizadas.
- Visualizar o número total de metas criadas.
- Monitorar a data e o horário em que cada meta foi concluída.
- Acompanhar a porcentagem de metas concluídas ao longo da semana.

## ⚙️ Funcionalidades

- **Cadastro de metas**: Permite que o usuário adicione metas para serem concluídas ao longo da semana.
- **Armazenamento de metas**: Exibe a quantidade total de metas criadas.
- **Monitoramento de conclusão**: Armazena a data e a hora em que cada meta foi concluída.
- **Cálculo de desempenho**: Exibe a porcentagem de metas concluídas ao final de cada semana.

## 🖥️ Tecnologias Utilizadas

- **Ambiente de Execução**: `Node.js`
- **Servidor Web**: `Fastify` 
- **Controle de Acesso**: `CORS` 
- **Banco de Dados**: `PostgreSQL`
- **Validação de Dados**: `Zod` 
- **Linting e Formatação**: `Biome.js`
- **Migração e Gerenciamento de Banco de Dados**: `Drizzle-kit`
- **Linguagem**: `TypeScript`

## ⚒️ Instalação

### Pré-requisitos

Antes de começar, você precisará ter as seguintes ferramentas instaladas:
- [Node.js](https://nodejs.org/en/)
- [Git](https://git-scm.com/)
- [Docker](https://www.docker.com/)
- [Postman](https://www.postman.com/)

### Configurando o Backend

O projeto depende de um backend que deve ser clonado e configurado separadamente. Siga os passos abaixo para configurar o backend:

**1.** Clone o repositório do backend:

```bash
git clone https://github.com/devnestali/server_inorbit.git
```

**2.** Escreva no seu terminal os seguintes comandos para poder criar as tabelas do banco de dados: 

```bash
npx drizzle-kit generate
```

```bash
npx drizzle-kit migrate
```

**3.** Crie um container dentro do Docker: 

```bash
docker compose up -d
```

**4.** (Opcional) Escreva o comando abaixo no seu terminal para criar metas padronizadas:

```bash
npm run seed
```

**5.** Por fim, para rodar o Back-end escreva no seu terminal: 

```bash
npm run dev
```

**6.** Se ainda não configurou o Front-end, acesse a URL abaixo e siga as intruçõesÑ 

```bash
https://github.com/devnestali/web_inorbit
```