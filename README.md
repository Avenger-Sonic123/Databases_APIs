# Database and API Learning — Prisma

A PostgreSQL data-modeling exercise using Prisma and generated JavaScript client files.

**Repository created:** 2025-07-04  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2025-07-04

## Features and implementation

- User model with auto-incrementing ID, name, unique email and age.
- SQL migration with primary key and unique index.
- Generated Prisma client artifacts.

## Technologies

PostgreSQL, Prisma, SQL, JavaScript (generated client).

## How the code works

The schema and SQL migration define a `User` table with an integer primary key and a unique email column. The JavaScript client files are generated artifacts, not a standalone API implementation.

## Project structure

| File | Purpose |
| --- | --- |
| [`schema.prisma`](schema.prisma) | Prisma schema and database configuration |
| [`migration.sql`](migration.sql) | SQL table and index definitions |
| [`package.json`](package.json) | Generated client package metadata |
| [`index.js`](index.js) | Generated Prisma client entry point |

## Run or explore locally

Review schema.prisma and migration.sql; use a separate Node.js/Prisma project and test PostgreSQL database to experiment.

The schema reads the connection string from `DATABASE_URL`. Do not commit credentials. No runnable application or complete dependency setup is included in this export.

## Current status and limitations

No application entry point, HTTP API routes or server implementation are present. The generated files are flattened at repository root.

## Related project snapshots

Other repositories in this project family:
- [Databases_APIs_TEST](https://github.com/Avenger-Sonic123/Databases_APIs_TEST) — repository created 2025-07-05

---

Source reference: [`042331bc`](https://github.com/Avenger-Sonic123/Databases_APIs/tree/042331bcf45f63cc31cb0204de3f5b90327b8d27) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
