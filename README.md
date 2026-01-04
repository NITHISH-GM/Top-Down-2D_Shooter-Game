# Top-Down 2D Shooter Game

A simple, browser-playable top-down 2D shooter implemented with HTML5 Canvas and vanilla JavaScript.

Features
- Player movement (WASD / arrow keys)
- Mouse aiming + left-click shooting (or Space to shoot)
- Enemies spawn and move toward the player
- Collisions: bullets vs enemies, enemies vs player
- Score, health, and game over / restart
- Lightweight and easy to extend (add sprites, audio, power-ups, etc.)

Controls
- Move: W / A / S / D or Arrow keys
- Aim: Move the mouse
- Shoot: Left mouse button or Space
- Restart after game over: R

How to run
1. Clone or download the repository.
2. Place these files at the repository root (or a folder):
   - `index.html`
   - `style.css`
   - `main.js`
3. Open `index.html` with a modern browser (Chrome, Firefox, Edge).
   - You can open it directly from the filesystem or serve with a simple static server:
     - Python 3: `python -m http.server 8000` then visit `http://localhost:8000/`

Project structure
- index.html — Container and canvas
- style.css — Basic layout and responsive canvas
- main.js — Game logic (input, entities, loop, rendering)

Extending the game (ideas)
- Add sprites and animations (replace circle drawings with images)
- Add audio for shooting, hits, and background music
- Add different enemy types and spawn patterns
- Add player upgrades, power-ups, score multipliers
- Mobile-touch controls support

Contributing
- Create a branch for each feature/fix.
- Open a PR with a clear description and testing notes.

License
- This project is provided as-is. Add a license file if you want to choose one (MIT recommended).

Enjoy! If you want, I can:
- Push these files to your GitHub repo
- Convert to a TypeScript project
- Add assets, audio, or a build pipeline
