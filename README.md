## Prerequisites
* Installed Node.js
* Postgres, PgAdmin
* Docker
* NPM dependencies

## Installation
1. Initialize Prisma in current directory `prisma init`
2. Expose your Postgres port in `./docker-compose.yml`
3. Run `docker-compose up`
4. Run `prisma deploy`
5. Open `http:localhost:4466`
