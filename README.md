# Node Typescript ESM

Minimalistic project template for a Node.js & TypeScript apps with native ESM

## Features

- 💎 Node.js 18+
- 🛠️ TypeScript 5.3
- ⚡️ [tsx: Node.js enhanced to run TypeScript & ESM files](https://github.com/privatenumber/tsx)
- 📁 [tsc-alias: Import path alias using `@/` prefix](https://github.com/justkey007/tsc-alias) 
- 🔍 ESLint — To find and fix problems in your code
- 📝 Prettier — Format your code consistently
- 🌍 Express.js


## Quick Start

### 1. Clone repo

clone repo without commit history

```bash
git clone --depth=1 https://github.com/ibnumusyaffa/node-typescript-esm-starter my-project-name
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the development server

```bash
npm run dev
```
1. Check it out: [http://localhost:8080](http://localhost:8080)

## Available scripts

- `npm run dev` — Starts the application in development mode at.
- `npm run build` — Compile the application.
- `npm start` — Starts the application in production mode.
- `npm run lint` — Check code using ESLint.
- `npm run lint:fix` — Fix autofixable ESLint problem.
- `npm run format:all` — Format code using Prettier for all files.
- `npm run format:check` — Check code format using prettier.

## Run Locally with Buildpacks & Docker:
```
pack build --builder=gcr.io/buildpacks/builder autoclocking
docker run -it -p8080:8080 sample-node-tsc autoclocking
```

Run on Cloud Run:

[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run)

Sample Node w/ TypeScript
-------------------------

Run Locally:
1. [Install Node](https://nodejs.org/en/download/)
1. Install Node modules
    ```
    npm install
    ```
1. Start the dev server:
    ```
    npm run dev
    ```
1


