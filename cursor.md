# Cursor

Project notes for this workspace.

## About

This is a **Node.js** app built with **TypeScript** and **Next.js**. Use this stack for all new files, features, and examples unless the user asks otherwise.

## Tech stack

- Runtime: Node.js
- Language: TypeScript (strict)
- Framework: Next.js (App Router)
- Package manager: npm
- Styling: CSS Modules or Tailwind CSS when UI work starts
- API: Next.js Route Handlers (`app/api`)

## Conventions

- Use TypeScript everywhere (`.ts` / `.tsx`); do not add new JavaScript files
- Prefer App Router (`app/`) over Pages Router
- Use React Server Components by default; add `"use client"` only when needed
- Keep types explicit for public APIs, props, and data models
- Colocate feature files (page, components, styles) when it stays readable

## Commands

```bash
npm install
npm run dev
npm run build
npm run start
npm run lint
```

## Project

- Name: test-project
- Status: stack decided; app not scaffolded yet
