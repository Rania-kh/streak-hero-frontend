# StreakHero Frontend 🌟

**StreakHero** is a gamified habit tracker. This repository contains the **frontend** built with **Vue 3, Vite, and Pinia**.

---

## Project Overview

The frontend is responsible for:

- Displaying user habits and streaks
- Creating, editing, and deleting habits
- Logging habit completions
- Showing XP and level progression
- Communicating with the backend via API calls

---

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

---

## Type Support for `.vue` Imports in TypeScript

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

---

## Customize Configuration

See [Vite Configuration Reference](https://vite.dev/config/).

---

## Project Setup

```bash
npm install
```

### Compile and Hot-Reload for Development

```bash
npm run dev
```

### Type-Check, Compile and Minify for Production

```bash
npm run build
```

---

## Testing

### Unit Tests with [Vitest](https://vitest.dev/)

```bash
npm run test:unit
```

### End-to-End Tests with [Cypress](https://www.cypress.io/)

```bash
npm run test:e2e:dev
```

This runs the E2E tests against the Vite dev server.

For testing the production build (recommended for CI):

```bash
npm run build
npm run test:e2e
```

---

## Linting & Formatting

```bash
npm run lint   # Check for linting issues
npm run format # Auto-format code if Prettier is set up
```

---

## Project Structure

```
streak-hero-frontend/
│── public/          # Static assets
│── src/
│   ├── __test__/
│   ├── router/      # Vue Router setup
│   └── main.ts      # Entry point
│── index.html
│── package.json
│── vite.config.ts
│── README.md
```

---

## Notes

- Ensure the backend is running for full functionality.
- Follow coding standards with ESLint and Prettier.
- For larger projects, keep components modular and organized by feature.
- This frontend is designed to communicate with the **StreakHero backend** API.
