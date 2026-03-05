# Forge Core

Nervous system regulation and impulse interruption micro-tool.

## Features

- **Morning Check-In** — Log body state, emotion, intensity, and a guiding principle
- **Evening Check-Out** — Track rumination, pauses, triggers, and daily wins
- **Break Glass** — Multi-step trigger interruption flow with breathing exercise and 15-minute pause timer
- **History** — Review past entries and patterns
- **Streak tracking** — Consecutive days with both AM and PM check-ins

## Tech

- Single `index.html` — all HTML, CSS, and JS inline
- Hash-based routing for GitHub Pages compatibility
- localStorage only — no backend, no accounts
- PWA-ready with service worker (network-first) and manifest

## Deploy

Hosted on GitHub Pages at `jddb74.github.io/forge-core`.

To run locally, serve the directory with any static server:

```bash
npx serve .
```

Or just open `index.html` directly in a browser.

## Data

All data stored in `localStorage` under the key `forge_core_data`. Use the "Reset Data" link on the home page to clear everything.
