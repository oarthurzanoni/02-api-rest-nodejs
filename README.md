# Transactions REST API

A REST API for recording credit and debit transactions and calculating an account summary.

## Project goal

Practice core backend concepts with Fastify, including HTTP routing, cookies, database queries, migrations and automated tests.

## Features

- Create credit and debit transactions
- List transactions for the current session
- Retrieve an individual transaction
- Calculate income, outcome and balance summaries

## Technologies

- **TypeScript**
- **Node.js**
- **Fastify**
- **Knex**
- **PostgreSQL / SQLite**
- **Zod**
- **Vitest**
- **Supertest**

## What I learned

- Designing resource-oriented REST endpoints
- Tracking a client session with cookies
- Writing database migrations and queries with Knex
- Testing HTTP routes and persistence behavior

## Running locally

```bash
npm install
npm run knex -- migrate:latest
npm run dev
```

## About this repository

This repository documents a learning project and the technical decisions explored while building it. It is not presented as a production-ready system.
