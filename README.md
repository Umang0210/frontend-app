# Frontend App (React + Vite)

A React-based e-commerce frontend built with Vite. Users can browse products, manage a cart, and place orders after authenticating.

## Prerequisites

- Node.js 20 or 22
- npm 10+

## Environment Variables

Create a `.env` file in the project root with:

```env
VITE_API_URL=http://localhost:5000
```

`VITE_API_URL` is used by the UI components to call the backend API.

## Install

```bash
npm ci
```

## Run Locally

```bash
npm run dev
```

By default, Vite runs on `http://localhost:5173`.

## Lint

```bash
npm run lint
```

## Build

```bash
npm run build
```

## Preview Production Build

```bash
npm run preview
```

## CI

GitHub Actions runs on pushes and pull requests to `main` and `master` (and can also be run manually).

CI checks:

- Install dependencies (`npm ci`)
- Lint (`npm run lint`)
- Build (`npm run build`)

Node versions tested in CI: 20.x and 22.x.
