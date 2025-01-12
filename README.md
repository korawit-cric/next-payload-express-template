# Turborepo: NextJs + Vite + Express + Storybook Template

This is an official starter Turborepo with multiple meta-frameworks all working in harmony and sharing packages.

This example also shows how to use [Workspace Configurations](https://turbo.build/repo/docs/core-concepts/monorepos/configuring-workspaces).

## What's inside?

This Turborepo includes the following packages and apps:

### Apps and Packages

- `api`: an [Express](https://expressjs.com/) server
- `storefront`: a [Next.js](https://nextjs.org/) app
- `admin`: a [Vite](https://vitejs.dev/) single page app
- `workshop`: Component documentation/workshop site with 📖 [Storybook](https://storybook.js.org/) — UI component environment powered by Vite

*Remark: Most of the packages yet be integrated into payload frontend
- `@repo/eslint-config`: ESLint configurations used throughout the monorepo
- `@repo/jest-presets`: Jest configurations
- `@repo/cric-ui`: prebuilt component with tailwind and cn utilities
- `@repo/typescript-config`: tsconfig.json's used throughout the monorepo

Each package and app is 100% [TypeScript](https://www.typescriptlang.org/).

## Running the Project

To set up and run the project, follow these steps:

### Step 1: Start Docker Containers

Run the following command to start the Docker containers (Postgres, Directus, etc.):

```bash
npm run docker:up
```
```bash
npx mikro-orm migration:up
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

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Jest](https://jestjs.io) test runner for all things JavaScript
- [Prettier](https://prettier.io) for code formatting
