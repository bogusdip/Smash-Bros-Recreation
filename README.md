# Smash Bros-Inspired Fighting Game

![Gameplay demo](https://cdn.imageurlgenerator.com/uploads/3ee6d854-1fa6-4e6c-bb19-c9170057290b.gif)

A local 2-player fighting game built with p5.js, inspired by Super Smash Bros' core mechanics. Players fight with a percentage-based damage system — as damage increases, knockback force increases (via a physics-based velocity/easing curve), eventually launching a player off-stage for a KO. Includes a dynamic camera that zooms and pans based on player distance, a stage with a main platform and floating platforms, wall-climbing/hanging, rolling with cooldowns, directional attacks (up/down/left/right) with distinct startup/active/recovery animation states, and visual effects (hit smoke, death particle lines, screen shake).

**[Play it / view the code in the p5.js editor →](https://editor.p5js.org/lucas.airewele/sketches/8dts0fH8i)**

## Controls

| Player | Move | Jump | Roll | Light Attack | Heavy Attack |
|--------|------|------|------|---------------|---------------|
| Player 1 | A / D | W | S | Q | E |
| Player 2 | J / L | I | K | U | O |

## Features

- Percentage-based damage and knockback system with eased physics
- Dynamic camera zoom/pan based on player distance
- Directional attacks (up/down/left/right) with distinct startup, active, and recovery animation frames
- Wall-climbing and wall-hanging near stage edges
- Rolling with a cooldown-based dodge window
- Screen shake, hit smoke particles, and death-effect line rendering
- Lives system with respawn and win-condition handling

## Notes

This was built as a personal project to learn state machines, physics-based movement, and animation timing in a game context. The code is dense in places — the header comment in the source recommends collapsing/minimizing helper functions before reading through the main game loop.
