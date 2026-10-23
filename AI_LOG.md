# GRAVITY FLIP ROOMS
## Complete Project Overview, AI Usage Report, and Prompts

### 1. Project Overview

**Project Name:** Gravity Flip Rooms  
**Project Type:** 2D browser-based physics puzzle platformer  
**Technologies Used:** HTML, CSS, JavaScript, Canvas API  
**Deployment:** GitHub Pages  
**Project Purpose:** To create an interactive puzzle game in which players manipulate gravity to navigate obstacles, solve room-based challenges, and reach the exit.

Gravity Flip Rooms is a browser game built around a simple but challenging idea: instead of moving only across the floor, the player can change the direction of gravity to move through different parts of a room. Players must think strategically, understand the environment, avoid hazards, and use their limited gravity flips carefully.

The project combines physics-based gameplay, puzzle-solving, visual design, and AI-assisted development. It was developed as a hackathon project, with the aim of transforming a basic game concept into a more polished and engaging experience.

### 2. Main Game Features

1. **Eight puzzle rooms:** A sequence of rooms with different challenges and objectives.
2. **Four-direction gravity:** Gravity can be changed to DOWN, LEFT, UP, or RIGHT.
3. **Room progression:** Players advance through rooms by completing the required objectives.
4. **Keys and exits:** Players collect keys to unlock exits and progress.
5. **Optional crystals:** Collectible crystals provide an additional challenge and bonus credit.
6. **Gravity Preview:** Players can preview the effect of the next gravity change before committing to it.
7. **Moving platforms:** Platforms introduce timing and movement challenges.
8. **Falling blocks:** Environmental objects add additional physics-based obstacles.
9. **Moving hazards:** Players must observe hazards and plan their movements carefully.
10. **Interactive puzzles:** Depending on the room, mechanics can include switches, pressure plates, linked doors, timed doors, and movable blocks.
11. **Limited gravity flips:** A flip limit encourages players to plan their moves rather than change gravity randomly.
12. **Time and performance tracking:** The interface displays elapsed time and can support medal-based performance evaluation.
13. **Pause and restart controls:** Players can pause the game or restart a room.
14. **Background soundtrack:** The game supports background music with a music toggle.
15. **Themed environments:** Visual themes include ancient temples, jungle ruins, and clockwork-inspired environments.
16. **Horizontal room selector:** Rooms are presented in a horizontal navigation layout.
17. **Game HUD:** The interface displays room number, gravity direction, remaining flips, key status, game status, time, and crystal status.
18. **Browser-based access:** The game can be opened in a supported web browser without installing a separate game application.

*Note: The exact availability of each mechanic may vary by room and final implementation. Only demonstrate features that are working in the submitted version.*

### 3. AI Tools Used or Explored

The following six tools were considered for different parts of the project. In the final submission, retain a tool as a contributor only if it was genuinely used.

**1. ChatGPT — Brainstorming and Development Assistance**

Purpose:
- Brainstorming the game concept and mechanics.
- Planning room progression and possible improvements.
- Organizing feature lists and implementation steps.
- Preparing code-related guidance, testing checklists, documentation, and presentation material.

**2. Kiro — Requirements and Task Planning**

Purpose:
- Structuring the project requirements.
- Breaking larger features into smaller development tasks.
- Defining dependencies and acceptance criteria.
- Planning edge cases and manual testing.

**3. Google Stitch — User Interface Design**

Purpose:
- Exploring visual concepts for the game interface.
- Planning the HUD, room navigation, status indicators, and completion screen.
- Exploring a consistent visual style for the themed environments.

**4. Suno AI — Background Music**

Purpose:
- Exploring or generating an original instrumental soundtrack.
- Establishing a mysterious, adventurous, and cinematic atmosphere.
- Creating music intended to support concentration during puzzle-solving.

**5. OpenAI Codex — Coding Assistance**

Purpose:
- Reviewing the existing HTML, CSS, and JavaScript structure.
- Assisting with incremental code improvements and debugging.
- Reviewing gameplay logic and asset references.
- Preparing testing suggestions and identifying possible issues.

**6. Google Antigravity — Agent-Assisted Development**

Purpose:
- Exploring repository analysis and development workflows.
- Reviewing the organization of game logic, controls, assets, and progression.
- Planning code-quality checks and testing.
- Identifying potential improvements while preserving existing working features.

### 4. How AI Was Used in the Project

AI tools were treated as assistants rather than replacements for development and decision-making. Each tool had a specific intended role, including ideation, planning, interface exploration, programming support, or audio creation.

The general workflow was:

1. Define the game concept and core mechanics.
2. Identify features that could make the game more interesting.
3. Organize features into manageable implementation tasks.
4. Explore interface designs and visual themes.
5. Develop and refine the existing game code.
6. Integrate suitable assets and audio.
7. Review controls, gameplay, and room progression.
8. Prepare documentation and the hackathon presentation.

AI-generated suggestions needed to be reviewed for suitability before being included. The project team remained responsible for selecting features, integrating changes, checking the final result, and presenting the game.

### 5. AI Prompts

The following are project-specific prompt examples prepared for the corresponding tools. They are **reconstructed prompts for documentation**, not necessarily verbatim records of the original conversations. Use them as evidence of actual usage only where they match the work performed.

#### Prompt 1: ChatGPT — Game Concept and Feature Planning

```text
Act as a game designer and technical mentor for my hackathon project, Gravity Flip Rooms.

It is a 2D browser puzzle platformer built with HTML, CSS, vanilla JavaScript, and Canvas. The player can flip gravity between DOWN, LEFT, UP, and RIGHT to solve physics puzzles.

The game has eight themed rooms, keys, optional crystals, heavy and light blocks, moving platforms, pressure plates, linked and timed doors, switches, falling blocks, moving hazards, a gravity preview, medals, personal bests, and a background soundtrack.

Review this feature list and suggest practical improvements without expanding the scope too much. Prioritize gameplay clarity, level variety, UI consistency, accessibility, and hackathon presentation.

Give me an implementation checklist and a test plan. Do not claim anything has been implemented or tested unless it actually has.
```

#### Prompt 2: Kiro — Requirements and Implementation Planning

```text
I am developing Gravity Flip Rooms, a browser-based 2D gravity puzzle game using HTML, CSS, JavaScript, and Canvas.

Create a concise feature specification and task plan for improving an existing game rather than rewriting it.

Features include:
- Eight distinct rooms with different objectives and visual themes.
- Four-direction gravity and a gravity preview.
- Moving platforms, falling blocks, and moving hazards.
- Heavy and light blocks, pressure plates, switches, and doors.
- Optional crystals, medals, completion times, and personal bests.
- A horizontal room selector and background music.

Break the work into small tasks with dependencies and acceptance criteria.

Include edge cases for collision detection, restarting a room, pausing, switching gravity, timed doors, and room progression.

Preserve the existing architecture and identify what needs manual testing.
```

#### Prompt 3: Google Stitch — UI Design and Prototyping

```text
Design a polished UI concept for Gravity Flip Rooms, a 2D gravity puzzle platformer for a college hackathon.

Visual direction: cinematic fantasy ruins inspired by three environments:
1. Ancient temple with teal and gold lighting.
2. Overgrown jungle ruins with lush greens.
3. Clockwork ruins with bronze and warm orange lighting.

Create a desktop game screen design with:
- A large central gameplay canvas.
- An eight-room selector displayed horizontally in one row.
- Room number, room title, and difficulty.
- Gravity direction indicator for DOWN, LEFT, UP, and RIGHT.
- Key and optional crystal status.
- Flip count, elapsed time, and objective text.
- Gravity Preview, Pause, Restart, and Music controls.
- A completion panel showing medal, time, flips used, and Continue/Restart actions.

Use readable typography, strong contrast, compact HUD components, subtle glow effects, and responsive behavior.

Keep gameplay as the main focus. Provide a visual prototype and component guidance. Do not claim the prototype is integrated into my existing code.
```

#### Prompt 4: Suno AI — Background Soundtrack

```text
Create an original instrumental background soundtrack for Gravity Flip Rooms, a fantasy-meets-futuristic 2D gravity puzzle game.

Mood: mysterious, adventurous, curious, and cinematic, with a sense of ancient ruins and magical machinery.

Sound palette: atmospheric synth pads, delicate electronic pulses, soft arpeggios, subtle metallic textures, and gentle orchestral accents.

The track should support concentration while players solve puzzles and flip gravity in four directions.

Requirements:
- Instrumental only, with no vocals or lyrics.
- A seamless-loop feeling suitable for continuous gameplay.
- Moderate intensity and no sudden loud impacts.
- Avoid recognizable melodies or imitation of existing game soundtracks.
- Balanced mixing so the music can sit quietly beneath sound effects.

Create a game-friendly ambient track. If possible, also provide short separate effects for gravity flipping, collecting a crystal, activating a switch, opening a door, and completing a room.
```

#### Prompt 5: OpenAI Codex — Code Review and Improvements

```text
Work on my existing Gravity Flip Rooms repository. It is a browser-based 2D puzzle game using HTML, CSS, vanilla JavaScript, Canvas, image assets, and an MP3 soundtrack.

First inspect the current files and summarize the architecture. Do not replace the game with a fresh implementation.

Review and improve these areas incrementally:
1. Eight-room progression and room-specific objectives.
2. Four-direction gravity and collision behavior.
3. Moving platforms, falling blocks, and moving hazards.
4. Pressure plates, switches, linked doors, and timed doors.
5. Optional crystals, medals, completion times, and personal-best records.
6. Gravity Preview preserving real game state.
7. Horizontal room selector and themed background assets.
8. Audio loading and the music toggle.

Make minimal, reviewable changes and preserve existing working features.

Run available syntax checks and tests. If browser testing is available, test each room and the key interactions.

Report the exact files changed, tests actually run, results, and any remaining issues.

Do not say a test passed unless it was executed. Do not rename or move assets without updating their paths.
```

#### Prompt 6: Google Antigravity — Repository Review

```text
Inspect my existing Gravity Flip Rooms project, a browser-based 2D gravity puzzle game built with HTML, CSS, JavaScript, and Canvas.

Before editing, map the main game loop, room configuration, collision handling, UI controls, asset paths, audio setup, and progression logic. Preserve the existing architecture.

Then create a careful review plan for:
- All eight rooms and their unique mechanics.
- Gravity flips in all four directions.
- Collision and moving-object behavior.
- Pressure plates, switches, linked doors, and timed doors.
- Crystal collection, medals, and personal-best storage.
- Gravity preview not mutating live game state.
- Horizontal room selector and responsive layout.
- Background images and soundtrack loading.

Apply only necessary fixes in small steps. Run available checks, and use browser testing if supported.

Provide a concise report of changes and test evidence. Clearly separate confirmed results from untested assumptions, and ask before destructive changes.
```

### 6. Testing and Verification Plan

The final version should be checked for the following:

- All eight rooms can be selected or reached through the intended progression.
- Gravity changes correctly in all four directions.
- Player movement and collisions behave as expected.
- Keys, exits, crystals, switches, and doors work as designed.
- Moving platforms, falling blocks, and hazards behave consistently.
- Gravity Preview does not unintentionally alter the live game state.
- Pause and restart controls work.
- The music toggle works and missing audio does not break gameplay.
- The room selector and HUD remain readable at different screen sizes.
- The game loads correctly from the published GitHub Pages URL.
- All images and audio files load from their deployed paths.
- The final game can be completed without a blocking bug.

Only report checks as passed if they have actually been performed. Any known issues should be disclosed rather than hidden.

### 7. Responsible AI Usage

AI-assisted development can speed up brainstorming, help organize requirements, explore visual ideas, and assist with coding. However, AI-generated output can contain mistakes, incomplete logic, or suggestions that do not fit the existing code.

For this project, responsible use means:
- Reviewing generated code before accepting it.
- Testing gameplay instead of assuming code is correct.
- Avoiding claims that a tool implemented a feature when it only suggested it.
- Confirming that generated or downloaded assets are suitable for the intended use.
- Keeping the project team's own decisions and work clearly represented.
- Recording which tools genuinely contributed to the final version.

### 8. Final Project Statement

Gravity Flip Rooms demonstrates how a familiar platform-game concept can be developed into a puzzle experience using four-direction gravity and room-based challenges. The project combines browser technologies with themed environments, interactive mechanics, a structured interface, and optional performance goals.

AI tools were considered for selected stages of development, including brainstorming, planning, UI exploration, programming support, and audio creation. Their output was intended to support the development process, while the project team remained responsible for implementation choices, integration, testing, and the final presentation.

The objective was not simply to make a playable game, but to create an engaging hackathon project that demonstrates creative thinking, technical problem-solving, iterative development, and transparent use of AI assistance.
