# Catalyst + Klevu

## Getting Started

1. Start by cloning this repository

```bash
git clone git@github.com:bigcommerce-labs/catalyst-klevu.git && cd catalyst-klevu
```

2. Ensure you are using the correct Node version

> [!TIP]
> If you're using [`nvm`](https://github.com/nvm-sh/nvm), you can run [`nvm install` to automatically read `.nvmrc` and install the correct Node version](https://github.com/nvm-sh/nvm?tab=readme-ov-file#nvmrc).

3. Use corepack to enable pnpm, then use pnpm to install project dependencies

```bash
corepack enable pnpm && pnpm install
```

4. Set up environment variables

```bash
cp .env.example .env.local
```

> [!TIP]
> You can run `pnpm create @bigcommerce/catalyst@latest init` to generate an `.env.local` file for your store.

5. Start the development server

```bash
pnpm dev
```
