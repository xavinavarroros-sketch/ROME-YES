# SPQR Railway App

React/Vite wrapper for the SPQR webapp.

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Railway

Railway settings:

- Build command: `npm run build`
- Start command: `npm run start`

The app includes a `window.storage` fallback using browser `localStorage`. This is enough for testing, but data is stored per browser. For shared multiplayer data, connect a database such as Supabase, Firebase, or Railway PostgreSQL.
