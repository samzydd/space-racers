# Space Racers

A single-file 3D space racing game. Twenty-two mail rockets launch from Aurora;
every level the field shrinks by two, so fly clean, grab the rings, and shoot
your way up the order.

**Play:** open `index.html` in any modern browser, or use the GitHub Pages link.

## Features

- 3rd-person **and** first-person / cockpit camera (`C`), with a live rear-view mirror
- Endless levels: 22 rockets on level 1, two fewer each level (routes cycle through three environments)
- Unlimited forward fire with target lock; rivals shoot back, with a directional "dodge" alert
- Weapon gems: amber = extra cannon (up to x3), violet = more firepower (colours your shots),
  green = seeker missiles that home onto a target. Firepower/cannons carry between levels
- Shots also blow up asteroids in your path
- Boost that burns out and needs to recharge; flaming BOOST rings give an acceleration surge
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

All keys are rebindable in the in-game **Controls & help** screen (from the menu or the pause menu). Touch controls (on-screen buttons) are provided on mobile.


## Tech

- [three.js](https://threejs.org/) r160 (loaded from a CDN)
- No build step — the entire game is `index.html`
