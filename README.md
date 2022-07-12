<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest


## Description

This is app parse RSS every 5 minutes.

Routes:

posts

POST /posts/{id}

GET /posts

GET /posts/{id}

PATCH /posts/{id}

DELETE /posts/{id}

Where {id} - ObjectId(_id) row in PostgreSQL DB.

Worker Task:

Parse RSS every 5 minutes and add posts to database PostgreSQL.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

If you want use Swagger - open link http://localhost:3000/api/#/posts/ after runnning the app.

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Support

SimpleParser is an Apache2.0-licensed open source project. 
Used in project:
-  [NestJS](https://docs.nestjs.com/)
-  [Docker](https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)
-  [PostgreSQL 14](https://www.postgresql.org/docs/14/index.html)
-  [Swagger](https://swagger.io/docs/specification/about/)  

## Stay in touch

- Author - [Maksym Tsiupko](https://www.linkedin.com/in/maksym-tsiupko-99853b137/)

## License

SimpleParser is [Apache 2.0 licensed](LICENSE).
