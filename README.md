# 🔴 Red Planet Staffing — Browser Simulation

A self-contained 3D Mars workforce visualizer. No install, no server — just open the HTML file in any modern browser.

---

## Running it

```
open index.html
```

That's it.

---

## What's Inside

All data is seeded directly in the file

- **15 workers** — Zara Voss, Kai Oduya, Mira Solano, and 12 others
- **8 workplaces** — Olympus Mining Rig, Valles Marineris Depot, Hellas Basin Refinery, and more
- **120 shifts** — 60% completed, 20% open, 20% cancelled

---

## Controls

| Action                 | What it does                                                                |
| ---------------------- | --------------------------------------------------------------------------- |
| **▶ NEXT SHIFT**       | Advances one tick — assigns a worker, animates travel, updates leaderboards |
| **⟳ AUTO RUN**         | Plays ticks automatically every 1.4s                                        |
| **TERRAIN / GLOBE**    | Switches between Mars surface and rotating planet view                      |
| **Click a building**   | Opens a detail popup for that workplace                                     |
| **Hover a worker dot** | Shows name, status, and completed shift count                               |
| **Drag + scroll**      | Orbit the camera and zoom                                                   |

## Worker Status Colors

| Color     | Meaning              |
| --------- | -------------------- |
| ⚫ Grey   | Idle                 |
| 🟡 Yellow | Travelling to a site |
| ⚪ White  | Working              |

---

## Vibe coded with cursor

- [Three.js r128](https://threejs.org) — 3D rendering
- Vanilla HTML/CSS/JS — no build step, no dependencies
