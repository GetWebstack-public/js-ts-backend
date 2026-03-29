# js-ts-backend — Hello World Templates

A set of ready-to-run "Hello World" backend templates for the most popular JavaScript and TypeScript frameworks. Each template is a standalone starting point: **fork the one you want, run it with `gws`, and start building**.

## Available Templates

| Template | Language | Framework |
|----------|----------|-----------|
| [nestjs](./nestjs) | TypeScript | [NestJS](https://nestjs.com/) |
| [nodejs-adonisjs](./nodejs-adonisjs) | TypeScript | [AdonisJS](https://adonisjs.com/) |
| [nodejs-elysia](./nodejs-elysia) | TypeScript | [Elysia](https://elysiajs.com/) |
| [nodejs-express](./nodejs-express) | JavaScript | [Express](https://expressjs.com/) |
| [nodejs-fastify](./nodejs-fastify) | JavaScript | [Fastify](https://fastify.dev/) |
| [nodejs-graphql-yoga](./nodejs-graphql-yoga) | JavaScript | [GraphQL Yoga](https://the-guild.dev/graphql/yoga-server) |
| [nodejs-hono](./nodejs-hono) | JavaScript | [Hono](https://hono.dev/) |
| [nodejs-koa](./nodejs-koa) | JavaScript | [Koa](https://koajs.com/) |
| [nodejs-trpc](./nodejs-trpc) | TypeScript | [tRPC](https://trpc.io/) |
| [typescript-generic](./typescript-generic) | TypeScript | Plain TypeScript |

## Getting Started

### 1. Pick a template and fork it

Browse the templates above, choose the framework you want to work with, and fork that repository into your own GitHub account.

### 2. Install the GetWebstack CLI

```bash
curl -sSL https://getwebstack.com/install.sh | bash
```

### 3. Initialise the project

Inside the forked project directory, run:

```bash
gws init
```

This connects the project to GetWebstack, pulls any required configuration, and sets up the local environment.

### 4. Start the application

```bash
gws up
```

The application will build and start locally. Each template returns a simple `Hello World` response to confirm everything is working.

### 5. Start developing

The templates are intentionally minimal — just enough to get a working server running. Add routes, middleware, database connections, and anything else your project needs.

> Some templates require secrets (e.g. API keys) to be configured in the GetWebstack app before running. Check the template's own `README.md` for any additional setup steps.
