# Pipe Mania

A browser-based Pipe Mania clone — single HTML file, no dependencies, no build step.

**[Play it](https://chrisflath.github.io/pipe-mania/)**

## How to play

Place pipes from the queue to connect the faucet to the target before the water starts flowing. The longer your route and the more bonus tiles you hit, the higher your score.

- **Click** a grid cell to place the next pipe from the queue
- Pipes **cannot be replaced** once placed
- Water starts flowing automatically after the countdown — plan ahead!
- Route water through the **gold bonus tile** for extra points (level × 5)
- Reach the **star target** to complete the level
- You have **3 lives** — lose one each time the water runs dry

## Scoring

| Event | Points |
|-------|--------|
| Each pipe filled | +1 |
| Bonus tile | +level × 5 |
| Level complete | +level × 10 |
| Unfilled pipes (level end) | −1 each |

## Features

- **7 level colour palettes** — distinct visual theme per level, cycling after 7
- **7 chiptune music tracks** — each level has its own key, tempo and melody (Web Audio API, no files)
- **CROSS pipes** — support two independent flows on perpendicular axes
- **Bag queue system** — shuffled sets guarantee a balanced mix of corners, straights and crosses
- **High score leaderboard** — top 10 scores saved locally, enter your initials on game over
- **Lives system** — 3 lives; retry the same level on a life lost, full reset on game over
- Fully self-contained — one `index.html`, works offline

## Running locally

```
open index.html
```

Or serve with any static file server:

```
npx serve .
```
