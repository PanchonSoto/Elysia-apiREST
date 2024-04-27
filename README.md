# Elysia with Bun runtime

## Getting Started
To get started with this template, simply paste this command into your terminal:
```bash
bun create elysia ./elysia-example
```

## Development
To start the development server run:
```bash
bun run dev
```

Open http://localhost:3000/ with your browser to see the result.

## dev depencencies
```bash
bun add -d prisma
```
```bash
bunx prisma init --datasource-provider sqlite
```

## after create each prisma schema.
```bash
bunx prisma migrate dev
```
