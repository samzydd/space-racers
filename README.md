# Space Racers

A single-file 3D space racing game. Twenty-two mail rockets launch from Aurora;
every level the field shrinks by two, so fly clean, grab the rings, and shoot
your way up the order.

**Play:** open `index.html` in any modern browser, or use the GitHub Pages link.

## Features

- 3rd-person **and** first-person / cockpit camera (`C`), with a live rear-view mirror
- Endless levels: 22 rockets on level 1, two fewer each level (routes cycle through three environments)
- Forward weapons with target lock; rivals shoot back, with a directional "dodge" alert
- Boost that burns out and needs to recharge; teal rings give an acceleration surge
- Procedural rockets, asteroid fields, planets, nebulae — everything drawn in code
- Synthesised engine/SFX (no audio assets), light + dark theme aware

## Controls

| Key | Action |
| --- | --- |
| ← → | steer |
| ↑ ↓ | climb / dive |
| Shift | boost |
| Space | fire |
| S | brake |
| C | cockpit / chase camera |
| T | toggle incoming alerts |
| M | toggle sound |
| Esc | pause |

Touch controls (on-screen buttons) are provided on mobile.

## Tech

- [three.js](https://threejs.org/) r160 (loaded from a CDN)
- No build step — the entire game is `index.html`
