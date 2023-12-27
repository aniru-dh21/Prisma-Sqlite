# Building a Node.js Database using Prisma and SQLite

Prisma is a modern ORM (Object-Relational-Mapping tool) that works with Node.js and TypeScript.

SQLite is a self-contained database engine. This means that you don't need to configure a database on your computer.

## Requirements to build the project

- Node.js (12.2 or higher)

Before getting cloning project, take the time to double-check if you have version 12.2 or higher of <a href="https://nodejs.org/en/">Node.js</a>.

> **Note**: If you want to check your Node.js version, you can type: `node -v` in a terminal. The output will be the version.

## Build and run the project

Run the database migrations:

```
$ npx prisma migrate dev
```

Run the project:

```
$ npm run dev
```
