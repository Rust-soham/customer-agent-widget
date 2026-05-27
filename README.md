# Customer Agent Widget

AI-powered customer support widget and dashboard built as a TypeScript monorepo.

## Stack

- Next.js, React, Tailwind CSS
- Node.js, Express
- Prisma, PostgreSQL
- LangChain, LangGraph, Qdrant
- Turborepo, pnpm, Docker

## Structure

```text
apps/
  web/      Dashboard app
  widget/   Embeddable customer chat widget
packages/
  backend/  API and agent logic
  db/       Prisma schema and database client
  ui/       Shared UI components
```

## Setup

```bash
pnpm install
pnpm dev
```

Environment templates are available as `.env.example` files in the apps and packages that need them.

## Scripts

```bash
pnpm dev
pnpm build
pnpm lint
pnpm format
pnpm docker:dev
```

## License

MIT
