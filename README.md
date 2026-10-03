# nest-events-backend

A [NestJS](https://nestjs.com/) backend intended as the API counterpart to [nest-events-frontend](https://github.com/alejo86a/nest-events-frontend), a Vue 3 events/RSVP application.

## Status

This repository currently contains only the unmodified NestJS CLI boilerplate (a single `AppController` / `AppService` returning `"Hello World!"`). None of the events, authentication, or attendance logic implemented on the frontend side has actually been built here — the real API work for this project never went past scaffolding.

## Tech stack

- [NestJS](https://nestjs.com/) 8 (TypeScript)
- Express platform adapter
- Jest for unit/e2e tests

## Running the app

```bash
npm install

# development
npm run start

# watch mode
npm run start:dev

# production mode
npm run start:prod
```

## Tests

```bash
npm run test
npm run test:e2e
npm run test:cov
```

## Context

Personal practice project exploring NestJS, meant to be paired with a separate Vue 3 frontend. This backend is unfinished and left at CLI-boilerplate stage.
