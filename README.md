# cod-platform-web

Next.js dashboard — seller-facing UI for the COD Platform.

## Purpose

Frontend application for the COD Platform. Currently a Phase 1 placeholder; real dashboard UI ships in Increment 9.

## Setup

```bash
npm install
```

## Run

```bash
# development
npm run dev

# production build
npm run build
node server.js   # standalone output
```

## Environment Variables

| Variable | Description |
|---|---|
| `NEXT_PUBLIC_API_URL` | API base URL — baked in at build time. Use `http://localhost:3000` for local dev. |

## Stack

- Next.js (App Router, TypeScript)
- Tailwind CSS
- React 19
- Node 22
