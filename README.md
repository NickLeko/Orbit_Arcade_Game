# ORBIT

ORBIT is a browser arcade game where a pilot steers a rocket through hazards, pickups, and a local skin shop.

## Problem / Use Case

This repo is a compact playable arcade prototype. It is meant to run directly in the browser and show a complete survival-game loop without requiring a build system or backend.

## Key Features

- Canvas-based rocket survival gameplay
- Keyboard and pointer steering
- Asteroids, aliens, planets, fuel, powerups, and coins
- Pilot profile setup with local save data
- Best score, total run stats, coin balance, and owned skins stored in `localStorage`
- Skin shop with unlockable rocket palettes
- Web app manifest and icon assets for browser install surfaces

## Tech Stack

- Static HTML
- Inline CSS and vanilla JavaScript
- Canvas 2D rendering
- Browser `localStorage`
- Web app manifest
- Google Fonts loaded from the page

There is no package manager, build step, backend, or database in the current repo.

## Run Locally

Open `index.html` directly in a browser, or serve the folder with a simple static server:

```bash
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000`.

## Current Status

This is a standalone MVP. Save data is local to the browser, gameplay tuning lives in `index.html`, and there are no automated tests or release scripts in the repo.
