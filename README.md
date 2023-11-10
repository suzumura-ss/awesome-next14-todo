Awesome Todo based on Next.js 14
===

## Getting Started

First, start database:

```bash
docker compose up
```

Second, run the development server:

```bash
# create database
yarn db:init

# and start dev server
yarn dev
```

Open [http://localhost:3001](http://localhost:3001) with your browser to see the result.

## Run test

```bash
yarn lint
# yarn test # not yet.
```

## Build image

```bash
docker build . -t todo:latest
```

## Run production mode

```bash
docker compose -f docker-compose-production.yml up --build
```
