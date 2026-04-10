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

### 1. Create a GetWebstack account

Sign up for a free account at [app.getwebstack.com](https://app.getwebstack.com). You'll need it to initialise and manage your projects with the `gws` CLI.

### 2. Pick a template and fork it

Browse the templates above, choose the framework you want to work with, and fork that repository into your own GitHub account.

### 3. Install the GetWebstack CLI

```bash
curl -sSL https://getwebstack.com/install.sh | bash
```

### 4. Log in to GetWebstack

```bash
gws login
```

This authenticates the CLI with your GetWebstack account.

### 5. Initialise the project

Inside the forked project directory, run:

```bash
gws init
```

This discovers the application and generates the necessary configuration files to run it locally.

### 6. Start the application

```bash
gws up
```

This builds the application and starts it in a local Kubernetes cluster. Each template returns a simple `Hello World` response to confirm everything is working.

### 7. Start developing

The templates are intentionally minimal — just enough to get a working server running. Add routes, middleware, database connections, and anything else your project needs.

> Some templates require secrets (e.g. API keys) to be configured in the GetWebstack app before running. Check the template's own `README.md` for any additional setup steps.

## Fullstack Templates

Looking for a frontend + backend starting point? Check out the fullstack templates:

| Template | Description |
|----------|-------------|
| [react-express-multi-repo](https://github.com/GetWebstack-public/react-express-multi-repo) | React frontend with an Express backend |

## Other Template Collections

| Collection | Description |
|------------|-------------|
| [.NET](https://github.com/GetWebstack-public/.NET) | Hello World templates for .NET (ASP.NET Core, Blazor, F#) |
| [go-projects](https://github.com/GetWebstack-public/go-projects) | Hello World templates for Go backends |
| [java](https://github.com/GetWebstack-public/java) | Hello World templates for Java and JVM languages |
| [js-ts-frontend](https://github.com/GetWebstack-public/js-ts-frontend) | Hello World templates for JavaScript and TypeScript frontends |
| [php](https://github.com/GetWebstack-public/php) | Hello World templates for PHP backends |
| [python-projects](https://github.com/GetWebstack-public/python-projects) | Hello World templates for Python backends |
