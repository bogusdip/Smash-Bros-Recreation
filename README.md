# Smash Bros-Inspired Fighting Game

<img width="720" height="406" alt="p5 js Web Editor _ Smash Bros Recreation FINAL_ - Opera 2026-09-15 21-55-17 (1)" src="https://github.com/user-attachments/assets/25283cb5-8f5a-4abc-9520-11851762a94e" />

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
