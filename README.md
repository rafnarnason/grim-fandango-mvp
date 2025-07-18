# Grim Fandango MVP

This is a minimal 3D adventure game prototype inspired by classic adventure games, built with TypeScript and Three.js. The project demonstrates interactive navigation, procedural ground textures, and simple character animation in a browser environment.

## Live Demo

Test the latest version here: [https://rafnarnason.github.io/grim-fandango-mvp/](https://rafnarnason.github.io/grim-fandango-mvp/)

## Features
- **Three unique screens** with different camera angles and navigation hotspots.
- **Procedural ground textures** for all screens:
  - Screen 1: Checkerboard pattern
  - Screen 2: Stripes pattern
  - Screen 3: Fishbone pattern
- **Interactive red box** on each screen that displays a message when clicked or approached.
- **Simple stick-figure player** with basic walking animation.
- **No external image textures**—all ground textures are generated procedurally in code.

## Major Decisions
- **Procedural Textures Only:** All static image textures were removed. Stone, grass, and checkerboard are now generated using canvas code for clarity and flexibility.
- **Overlay Messaging:** Overlay messages appear when the player interacts with the red box, with improved logic to ensure visibility.
- **Debugging:** Debug logs and visual cues were added to aid troubleshooting and development.
- **No Asset Copying:** The Vite static copy plugin was removed as all assets are now procedural.

## How to Run Locally
1. Clone the repo and run `npm install`.
2. Start the dev server with `npm run dev`.
3. Open the local URL provided by Vite.

## License
MIT 