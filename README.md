# MONEX-P (Monorepo Next Express Payload Template)

A boilerplate template for building a modern monorepo architecture with Next.js, Express, and Payload. Designed to streamline development and enhance scalability for full-stack applications. 

## What's inside?

This Turborepo includes the following packages and apps:

### Apps and Packages

- `api`: an [Express](https://expressjs.com/) server
- `web`: a [Next.js](https://nextjs.org/) app
- `workshop`: Component documentation/workshop site with 📖 [Storybook](https://storybook.js.org/) — UI component environment powered by Vite
- `payload`:  A fully integrated headless CMS designed to manage and serve dynamic content through an intuitive interface and robust API

- `@repo/cric-ui`: prebuilt component with tailwind and cn utilities
- `@repo/eslint-config`: ESLint configurations used throughout the monorepo
- `@repo/typescript-config`: tsconfig.json's used throughout the monorepo

Each package and app is 100% [TypeScript](https://www.typescriptlang.org/).

## Running the Project

To set up and run the project, follow these steps:

### Step 1: Start Docker Containers

Run the following command to start the Docker containers (Postgres, Directus, etc.):

```bash
npm run docker:up
```

### Step 2: Start the Development Environment

Once the Docker containers are up and running, you can start the development environment by running:
```bash
npm i
```
```bash
npm run setup-env
```
```bash
npm run dev
```
