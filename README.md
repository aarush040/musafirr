# MUSAFIR — AI Travel Companion

A cinematic travel platform built with React 19, TanStack Start, Tailwind CSS v4 and Framer Motion.

## Run locally (VS Code)

1. Install **Node.js 18+** (https://nodejs.org)
2. Open this folder in VS Code
3. In the terminal:

```bash
npm install
npm run dev
```

4. Open http://localhost:8080

The `.env` file already contains the backend URL and publishable key, so auth and the AI assistant work out of the box. The splash video and ambience sound are bundled as real files in `src/assets/`, so the splash screen works offline too.

## What's inside

- `src/routes/` — all screens (splash, onboarding, auth, home, explore, destination details, AI chat, trips, profile)
- `src/components/musafir/` — reusable UI components
- `src/lib/` — data, AI functions and helpers
- `src/styles.css` — design system (midnight navy + amber, Instrument Serif + Inter)
- `src/assets/` — destination images, splash video, ambient audio

## Notes

- If port 8080 is busy: `npm run dev -- --port 3000`
- To build for production: `npm run build`
