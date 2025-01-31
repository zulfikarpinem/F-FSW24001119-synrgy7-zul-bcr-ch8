# Challenge 8 - Deployment

Pada challenge di chapter ke-8 ini, akan dilakukan proses deployment.

## Table of contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Quick Start](#quick-start)
  - [Entity Relationship Diagram](#entity-relationship-diagram)
  - [Endpoints](#endpoints)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The Challenge

1. Membuat fitur media dengan penerapan ESLINT
2. Melakukan deployment
3. Melakukan unit testing

### Entity Relationship Diagram

![](./erd.png)

### Endpoints

Base URL : `https://leading-alix-zul-labs-6423fb71.koyeb.app`

- ### Auth

| Endpoint               | Method | Description                          |
| ---------------------- | ------ | ------------------------------------ |
| `/api/v1/sign-in`      | POST   | Masuk menggunakan email dan password |
| `/api/v1/sign-up`      | POST   | Membuat akun baru                    |
| `/api/v1/user/current` | GET    | Mendapatkan data pengguna yang masuk |

- ### Cars

| Endpoint           | Method | Description                         |
| ------------------ | ------ | ----------------------------------- |
| `/api/v1/cars`     | GET    | Mengambil semua data mobil          |
| `/api/v1/cars/:id` | GET    | Mengambil data mobil berdasarkan ID |
| `/api/v1/cars`     | POST   | Menyimpan data mobil baru           |
| `/api/v1/cars/:id` | PUT    | Mengedit data mobil berdasarkan ID  |
| `/api/v1/cars/:id` | DELETE | Menghapus data mobil berdasarkan ID |

- ### Sizes

| Endpoint            | Method | Description                          |
| ------------------- | ------ | ------------------------------------ |
| `/api/v1/sizes`     | GET    | Mengambil semua data ukuran          |
| `/api/v1/sizes/:id` | GET    | Mengambil data ukuran berdasarkan ID |
| `/api/v1/sizes`     | POST   | Menyimpan data ukuran baru           |
| `/api/v1/sizes/:id` | PUT    | Mengedit data ukuran berdasarkan ID  |
| `/api/v1/sizes/:id` | DELETE | Menghapus data ukuran berdasarkan ID |

- ### Users

| Endpoint            | Method | Description                            |
| ------------------- | ------ | -------------------------------------- |
| `/api/v1/users`     | GET    | Mengambil semua data pengguna          |
| `/api/v1/users/:id` | GET    | Mengambil data pengguna berdasarkan ID |
| `/api/v1/users`     | POST   | Menyimpan data pengguna baru           |
| `/api/v1/users/:id` | PUT    | Mengedit data pengguna berdasarkan ID  |
| `/api/v1/users/:id` | DELETE | Menghapus data pengguna berdasarkan ID |

## My process

### Built with

- TypeScript
- Node.js
- PostgreSQL
- [Express.js](https://expressjs.com/) - Minimalist Web Framework for Node.js
- [Knex.js](https://knexjs.org/) - SQL Query Builder for JavaScript
- [Objection.js](https://vincit.github.io/objection.js/) - SQL-friendly ORM for Node.js
- [ESLint](https://eslint.org/) - Pluggable JavaScript Linter
- [Jest](https://jestjs.io/) - Delightful JavaScript Testing Framework
- [SuperTest](https://www.npmjs.com/package/supertest) - Provide a high-level abstraction for testing HTTP

### What I learned

1. ESlint
2. Unit Testing & TDD
3. Cloud and Server
4. Containerisasi & Deployment
5. CI/CD

## Author

- Mhd Zulfikar Pinem - [zulfikarm022@gmail.com](mailto:zulfikarm022@gmail.com)
