# Gravity Flip Rooms

**Gravity Flip Rooms** is a browser-based 2D puzzle platformer where players manipulate gravity to navigate challenging rooms, solve physics-based puzzles, collect keys, and escape.

Built with HTML, CSS, JavaScript, and the Canvas API, the game combines gravity-based movement with interactive objects, environmental hazards, collectibles, and increasingly difficult levels.

## Features

- **Four-direction gravity:** Switch between down, left, up, and right.
- **Eight unique rooms:** Progress through different challenges and environments.
- **Dynamic environments:** Moving platforms, falling blocks, and moving hazards.
- **Interactive puzzles:** Heavy and light blocks, pressure plates, switches, and linked doors.
- **Bonus crystals:** Discover optional collectibles to improve room results.
- **Medal system:** Earn bronze, silver, or gold based on your performance.
- **Personal bests:** Track your best completion times and gravity-flip efficiency.
- **Gravity preview:** Preview the next gravity direction and predicted movement where supported.
- **Room-specific visuals:** Temple, jungle, and clockwork-inspired environments.
- **Background music:** Includes the *Gravity Flow* soundtrack.
- **Responsive room selector:** Eight rooms arranged horizontally on desktop screens.
- **Browser-based gameplay:** No installation or compilation required.

## The Eight Rooms

| Room | Name | Difficulty | Main Challenge |
|---|---|---|---|
| 1 | The Awakening | Easy | Learn gravity mechanics, navigate moving platforms, and find a hidden crystal. |
| 2 | The Machinery | Medium | Solve block, pressure-plate, and linked-door puzzles. |
| 3 | Gravity Core | Hard | Activate switches and navigate narrow routes. |
| 4 | The Dropworks | Medium | Avoid falling blocks and find a safe path. |
| 5 | The Time Lock | Hard | Activate a timed switch and cross before the door closes. |
| 6 | The Pendulum | Hard | Navigate moving platforms and timed hazards. |
| 7 | The Risk Route | Medium | Choose between safer routes and risky shortcuts. |
| 8 | The Singularity | Expert | Combine gravity, switches, blocks, and hazards in the final challenge. |

## Controls

Use the controls displayed in the game interface for the current key bindings.

- Move and jump to navigate the environment.
- Flip gravity to change the direction of gravitational force.
- Use Gravity Preview to plan your next move.
- Pause or restart whenever necessary.
- Toggle the background music using the music control.

## Run Locally

1. Download the project files.
2. Keep the files arranged as follows:

   ```text
   Gravity-Flip-Rooms/
   ├── index.html
   ├── gravity-flow.mp3
   └── assets/
       ├── temple.jpg
       ├── jungle.jpg
       └── clockwork.jpg
   ```

3. Open `index.html` in a modern web browser.
4. If local browser restrictions interfere with loading assets or audio, serve the folder using a local HTTP server.

Keep the soundtrack and `assets` folder in their expected locations.

## Deploy on GitHub Pages

1. Upload `index.html`, `gravity-flow.mp3`, and the complete `assets` folder to the repository root.
2. Open **Settings → Pages**.
3. Select the `main` branch and the root (`/`) folder.
4. Save and wait for GitHub Pages to publish the site.
5. Open the published URL and verify that the game, backgrounds, and soundtrack load correctly.

## Testing Checklist

Before the final hackathon demonstration, verify:

- [ ] All eight rooms load and progress correctly.
- [ ] The room selector displays horizontally on desktop.
- [ ] Room backgrounds and theme labels update correctly.
- [ ] All four
