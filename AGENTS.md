# AGENTS.md — Asteroids game

## Run the game

- Open `index.html` directly in a browser (double-click works).
- Or use a local server: `npx serve .` then visit `http://localhost:3000`.
- No build step, bundler, or dependencies. The game runs purely in the browser via HTML5 Canvas.

## Controls

| Key | Action |
|-----|--------|
| `←` `→` | Rotate ship |
| `↑` | Thrust |
| `Espacio` | Shoot |

## Code structure

- All logic lives in `game.js` (ES6+, strict mode).
- Entry point: `index.html` → loads `game.js` → `requestAnimationFrame` loop.
- No frameworks, no config files, no npm scripts.

## Verification

- No test suite or linting configured. Play the game to verify visual behavior.
- If you modify `game.js`, reload the page to see changes.