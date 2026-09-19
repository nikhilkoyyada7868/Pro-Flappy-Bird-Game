<div align="center">

# Flappy Bird — Luxe Edition

### A polished, dependency-free browser game with adaptive difficulty, personalization, and a berry power-up.

![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black)
![No dependencies](https://img.shields.io/badge/Dependencies-None-22C55E)

</div>

## About the game

This project takes the familiar one-button Flappy Bird loop and treats it like a compact product-polish exercise. The core mechanic stays instantly understandable while animation, progression, saved personalization, and a risk-changing power-up add a more premium feel.

## Highlights

- Responsive HTML Canvas rendering
- Pointer/touch and keyboard controls
- Day-to-night animated sky, stars, clouds, mountains, and ground layers
- Bird animation, trail effects, sparks, collision particles, and screen shake
- Gradually increasing pipe speed and narrowing gaps
- Berry power-up that grants temporary invincibility for ten passed pipes
- Five selectable bird color themes
- Pause, resume, restart, score, and best-score states
- Best score and selected color saved in `localStorage`

## Play

Open `index.html` in a modern browser. For consistent local asset loading, serve the directory:

```bash
git clone https://github.com/nikhilkoyyada7868/Pro-Flappy-Bird-Game.git
cd Pro-Flappy-Bird-Game
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Controls

| Action | Control |
| --- | --- |
| Flap | Tap/click or press <kbd>Space</kbd> |
| Pause or resume | Use the on-screen button |
| Restart | Tap/click or press <kbd>Space</kbd> after game over |
| Change bird | Select a color swatch in the menu |

## How it is built

The game has no framework or package dependencies. `main.js` contains the game loop and small domain classes for the world, bird, pipes, particles, fruit, and UI state. Rendering is done directly on a full-screen canvas; `styles.css` handles the overlay controls and responsive presentation.

## What this project demonstrates

- Delta-time game loops and requestAnimationFrame
- Procedural drawing, gradients, parallax, and particles
- Simple physics and circle/rectangle collision detection
- State machines for menu, running, paused, and game-over states
- Progressive difficulty and browser-side persistence

## Note

This is a learning and portfolio project inspired by the classic Flappy Bird mechanic. It is not affiliated with the original game's creator or publisher.
