# Building a Fullstack Netflix Clone with NextJS, TailwindCSS & Prisma

This is a repository for a FullStack Netflix Clone tutorial using NextJS, TailwindCSS & Prisma.

Features:

- Environment, Typescript, NextJS Setup
- MongoDB & Prisma connect, Database creation
- Authentication with NextAuth, Google & Github Login
- Full responsiveness on all pages
- Cookie based authentication
- API and Controllers creation
- Detail-oriented effects and animations using TailwindCSS
- React SWR data fetching
- Zustand state management

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_JWT_SECRET=
NEXTAUTH_SECRET=
```


### Migrate Collections to your MongoDb Database

``` shell
npx prisma db push
```


### Setup Demo Data for Db i.e. movies

`` Insert movies data from movies.json to your MongoDb movies collection ``

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
