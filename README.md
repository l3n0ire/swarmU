# swarmU

A single-file roguelike bullet hell game. Survive increasingly difficult waves of enemies and bosses. Keep moving and pick upgrades as you level up.

## How to Play

Open [l3n0ire.github.io/swarmU](https://l3n0ire.github.io/swarmU/) directly in a browser

For the PS Vita browser (and other old ES5-only browsers), use [l3n0ire.github.io/swarmU/psvite](https://l3n0ire.github.io/swarmU/psvita) instead

## Controls

- `W A S D` / arrow keys — move
- `P` — pause
- Touch — drag anywhere to move
- Gamepad (Xbox/Playstation controller)
  - Left stick or d-pad — move / navigate level-up cards
  - Any button — confirm (start game, retry, resume, pick upgrade)

Note: some browsers only detect a gamepad after you press a button on it once.

## Debugging

Set `GP_DEBUG = true` near the top of the gamepad code in [index.html](index.html) to show a live readout of the detected controller's id, axes, and computed input in the bottom-left corner.
