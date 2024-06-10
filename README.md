## Requirements: System
# MacOS: [Install Documentation](https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/)
```bash
xcode-select --install
brew tap mongodb/brew
brew update
brew install mongodb-community@7.0
brew services start mongodb-community@7.0
```

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