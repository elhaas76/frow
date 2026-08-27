# Frow

A top-down browser game about a single-celled organism that grows more complex by eating
other organisms, inspired by the general concept of thatgamecompany's *flOw* (reimagined here
with an original geometric, glowing-outline art style).

## Play

Open [`frow.html`](frow.html) directly in a browser — no build step, no dependencies, no server.

- **Move**: mouse (desktop) or touch-drag (mobile)
- **Eat** glowing diamonds to grow a longer segmented chain (+1 point)
- **Avoid** glowing triangles — they cost you a point and a segment
- Reach 3 points to descend a level; each level is darker and harder than the last
- Growth persists across all three levels — until a giant frog swallows you whole at the end
  of level three and the cycle begins again

## Tech

Single self-contained HTML file: vanilla JavaScript, Canvas 2D rendering, and the Web Audio
API for procedurally synthesized sound effects and ambient drone. No frameworks, no external
assets.
