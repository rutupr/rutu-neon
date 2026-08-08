# FinShield Build Guide

This file was generated from the current repository state.

## Install dependencies

```bash
npm install
```

## Build the frontend

```bash
npm run build
```

This runs the existing Vite build script defined in `package.json`.

## Run the application locally

Backend:

```bash
npm run dev:server
```

Frontend:

```bash
npm run dev
```

Then open the URL shown by Vite, typically:

```text
http://localhost:5173
```

## Notes

- The project is configured as a Vite + React app.
- Backend server uses `server.js` and `express`.
- The repository already contains a `build.log` file from a previous build.
