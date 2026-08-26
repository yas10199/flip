# FLIP

A one-tap arcade game. Bloop never stops running — tap anywhere to flip direction, collect the glowing dots, and don't touch red.

**Play it:** https://yas10199.github.io/flip/

## How it works

- **One control.** Tap (or press space / any arrow key) to reverse Bloop's direction around the loop.
- **Score.** Every dot is worth more as the level climbs, with a combo bonus for collecting without pause, plus a point per second survived.
- **Hazards.** Blinkers phase solid on a timer and flash orange first. Patrollers pace a stretch of track. Sweeper beams rotate across the arena.
- **Special dots** (level 51+): speed, magnet, freeze, double points, and ghost — pass straight through obstacles.

## Difficulty

| Levels | What changes |
| --- | --- |
| 1–5 | Calm. Just dots. |
| 6–10 | Speed climbs. |
| 11–20 | Blinking obstacles. |
| 21–30 | Obstacles start moving. |
| 31–40 | The arena morphs shape. |
| 41–50 | Twistier paths — clover, figure-8, star. |
| 51–75 | Special dots appear. |
| 76–100 | The whole arena rotates, with sweeper beams. |
| 100+ | Everything at once, still climbing. |

## Running it

`index.html` is completely self-contained — no build step, no dependencies. Open it in a browser, or serve the folder with any static host.

Built with Canvas, Web Audio for the sound effects, and `localStorage` for the best score.
