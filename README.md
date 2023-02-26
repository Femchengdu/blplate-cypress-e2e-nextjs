# clone the repository

# install all dependencies

```sh
yarn install
```

# set up the database

```sh
yarn docker-compose
```

# create the .env file based on the template.env and put the database URL for your prisma client

# To populate the database, run

```sh
npx prisma migrate dev
```

# run application

```sh
yarn dev
```
