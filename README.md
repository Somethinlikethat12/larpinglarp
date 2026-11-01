# VOID//BREACH — Last Light

A self-contained HTML5 arena-survival game. No build step, framework, package install, server code, or external game assets required.

## Play

Open [index.html](./index.html) in a modern browser, or enable GitHub Pages for this repository and publish from the root of `main`.

## Controls

- **WASD / Arrow keys:** Move
- **Mouse:** Aim
- **Hold left mouse button:** Fire
- **Space:** Dash (brief invulnerability; cooldown)
- **P / Escape:** Pause
- **Touch:** Virtual movement stick, FIRE, and DASH controls

## Systems

- Endless escalating waves with three standard enemy archetypes.
- The Warden boss appears every fifth wave and fires radial projectile patterns.
- Enemies drop collectible energy; level-ups offer a choice of three upgrades.
- Twelve upgrade paths cover weapons, defense, mobility, critical hits, regeneration, drones, and energy collection.
- Procedural Canvas rendering, synthesized Web Audio effects, hit flashes, particles, screen shake, and responsive HUD.
- Best score is saved locally in the browser.

## Technical notes

The game is implemented in one dependency-free `index.html` file using Canvas 2D, Pointer Events, Web Audio, localStorage, and a time-based `requestAnimationFrame` loop. It is designed to run as a static site.
