## Install PostgresSQL

I use docker to install PostgreSQL

```bash
docker run --name postgres -e POSTGRES_PASSWORD=postgres -p 5432:5432 -d postgres
```

## Install Dependecies

I use `yarn` package manager to install NodeJS depencies

```bash
yarn install
```

## Run The Project

```bash
yarn start
```
