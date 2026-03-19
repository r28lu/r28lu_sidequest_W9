# Border Check Fox Platformer — Side Quest Week 9

## Group Members

- Rini Lu, r28lu, 21091404

## Description

A fox platformer game built on top of Side Quest 6, now extended with a **debug screen** and a **bonus second level** for Side Quest 9.

The player controls a fox navigating a tile-based world, collecting leaves, avoiding fire hazards, and defeating boar enemies. The game features synthesized sound effects, parallax scrolling backgrounds, and physics-based combat.

### SQ9 Additions — Debug Screen

A toggleable debug screen (press **P**) that pauses the game and provides developer tools for testing and balancing:

- **Moon Gravity Toggle (1):** Switches world gravity between normal (10) and moon gravity (3), making jumps floatier and changing platforming feel. Useful for testing level traversal and jump distances.
- **God Mode Toggle (2):** Makes the player invincible — fire and boar damage are ignored. Useful for exploring levels and testing without dying.
- **Hitbox Visibility Toggle (3):** Renders collision boxes for the player (green), ground sensor (cyan), boar enemies (red), and leaf collectibles (yellow). Useful for debugging collision detection and sprite alignment.
- **Level Warp (4):** Instantly loads the other level, allowing quick testing of both levels without needing to complete them.

The debug overlay also displays real-time stats: current level, score, health, and player coordinates.

### SQ9 Bonus — Level 2

A second, harder level is added. When the player collects all 15 leaves on Level 1, the game automatically transitions to Level 2 instead of showing the win screen. Level 2 features a tighter layout with more fire hazards, narrower platforms, and more challenging enemy placement. Collecting all 15 leaves on Level 2 triggers the final win screen.

### SQ6 Features (Retained)

- **Sound:** Five sound effects (jump, leaf collect, hit enemy, receive damage, background music) loaded from `.wav` files, with mute toggle (**M**).
- **Visual Feedback (SQ6 Bonus):** Red screen flash on taking damage for a multi-sensory audio-visual response.

## Setup and Interaction Instructions

1. Open `index.html` in Google Chrome (or view via GitHub Pages).
2. Use **A/D** or **Left/Right Arrow** to move, **W** or **Up Arrow** to jump, **Space** to attack.
3. Collect all 15 leaves to advance to Level 2, then collect 15 more to win.
4. Avoid fire and defeat boar enemies (3 hits each).
5. Press **M** to mute/unmute background music.
6. Press **P** to open the debug screen, then use **1/2/3/4** to toggle debug features.
7. Press **R** to restart when dead or after winning.

## Iteration Notes

### Post-Playtest

1. N/A (Side Quest — individual weekly assignment)
2. N/A
3. N/A

### Post-Showcase

1. N/A
2. N/A

## Assets

All sprite sheets, tile images, background layers, and bitmap font are stored in the `assets/` folder. Sound effects are stored in `assets/sfx/`. The fox, boar, leaf, and fire sprite sheets, tile sets, and background layers are sourced from free asset packs (credited in code comments). The bitmap font is used for all in-game text rendering.

## References

1. p5.js Foundation. (n.d.). _p5.js_. Retrieved February 26, 2026, from https://p5js.org/
2. Pockney, Q. (n.d.). _p5play_. Retrieved February 26, 2026, from https://p5play.org/
3. p5.js Foundation. (n.d.). _p5.sound library_. Retrieved February 26, 2026, from https://p5js.org/reference/p5.sound/
4. Shakiba, A. (n.d.). _Planck.js — 2D physics engine_. GitHub. Retrieved February 26, 2026, from https://github.com/shakiba/planck.js
5. Pope, L. (2013). _Papers, Please_ [Video game]. 3909 LLC. https://papersplea.se/
