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

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Maksym Tsiupko](https://www.linkedin.com/in/maksym-tsiupko-99853b137/)

## License

SimpleParser is [Apache 2.0 licensed](LICENSE).
