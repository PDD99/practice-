# tb-mw-ecom-next

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

```bash
yarn create next-app tb-mw-ecom-next --typescript
```

## Getting Started


```bash
yarn dev # Runs next dev to start Next.js in development mode
yarn build # Runs next build to build the application for production usage
yarn start # Runs next start to start a Next.js production server
yarn lint # Runs next lint to set up Next.js' built-in ESLint configuration
```
First, make sure `yarn.lock` is up to date:
```bash
yarn install
```

Second, run the development server:

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.


## General

### Add Packages
```bash
yarn add
```
or add to package.json and run:
```bash
yarn install
```

### CI Hooks Are Enabled

pre-commit hook rules are in `commitlint.config`

Commit messages

- lower case
- `<subject>: <message>` format
- `<subject>` options:

```bash
build: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
ci: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
docs: Documentation only changes
feat: A new feature
fix: A bug fix
perf: A code change that improves performance
refactor: A code change that neither fixes a bug nor adds a feature
style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
test: Adding missing tests or correcting existing tests
```
- example:
```
git commit -m 'build: added redux libraries'
```

## Major Libraries
- MUI (with CSS & Bootstrap)
- ReduxToolkit & Thunks (confirm once added)
- CI Husky (confirm)

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
