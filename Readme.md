# Backend Project

A learning project for understanding how a production backend is put
together: an API that combines the core features of YouTube and Twitter,
built with Node.js and Express.

## Status

This is the starting scaffold. The project structure, tooling and config are
set up. The files in `src/` (`index.js`, `app.js`, `constants.js`) are still
empty, so there is no running API yet. `public/temp/` is kept for temporary
file storage.

## Tech stack

- Node.js with ES modules
- Express (to be added as the API is built)
- nodemon for reloading during development
- Prettier for formatting

## Run locally

Requires Node.js 18 or later.

```bash
npm install
npm run dev
```

Environment variables go in a local `.env` file, which is git-ignored.
