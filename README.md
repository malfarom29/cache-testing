## Description

## Configuration
Set the following env variables:

```dotenv
REDIS_HOST=
REDIS_PORT=
REDIS_PASSWORD=
REDIS_TTL=
```

Start redis with `docker-compose up -d`

## Installation

```bash
$ yarn install
```

## Test

```bash
# unit tests
$ yarn test

# e2e tests
$ yarn test:e2e

# test coverage
$ yarn test:cov
```

