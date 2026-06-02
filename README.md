# React Vite Starter

A personal starter template with the boilerplate already done.

## Stack

- **React 19** + **TypeScript**
- **Vite** — fast dev server and build
- **TanStack Query v5** — data fetching and server state
- **Tailwind CSS v4** — utility-first styling
- **shadcn/ui** — accessible component primitives (Radix UI)
- **Inter** variable font via `@fontsource-variable/inter`

## Getting Started

```bash
pnpm install
pnpm dev
```

## Scripts

| Command | Description |
|---------|-------------|
| `pnpm dev` | Start dev server |
| `pnpm build` | Type-check and build for production |
| `pnpm preview` | Preview production build |
| `pnpm lint` | Run ESLint |

## Adding shadcn Components

```bash
pnpm dlx shadcn@latest add <component>
```

## TanStack Query

The `QueryClient` and `QueryClientProvider` are already wired up in `src/main.tsx`. React Query Devtools are included in dev builds.
