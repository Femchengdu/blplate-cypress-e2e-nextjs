# E2E testing using Cypress in a NextJs application

## install all dependencies

```sh
yarn install
```

## set up the database

```sh
yarn docker-compose
```

## create an .env file based on the template.env and put the database URL for your prisma client

## to populate the database, run

```sh
npx prisma migrate dev
```

## run application

```sh
yarn dev
```
