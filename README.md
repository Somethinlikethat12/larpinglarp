# ASHEN VOW — The Pilgrim's Descent

A self-contained, room-based action roguelite about reading enemy tells, committing to melee attacks, and surviving a descent through ruined sanctums.

## Play

Open [index.html](./index.html) in a modern browser, or publish the repository root with GitHub Pages. No build step or package installation is required.

## Controls

- **WASD / Arrow keys:** Move
- **Mouse:** Aim
- **Click / hold:** Strike with your blade
- **Space:** Dodge through danger (costs Resolve)
- **Shift:** Timed parry (stagger nearby attackers)
- **P / Escape:** Pause
- **Touch:** Virtual movement stick, Strike, and Parry buttons

## The combat loop

Each sanctum is a contained encounter. Read the enemy's wind-up, choose when to attack, dodge committed attacks, and use a timed parry to stagger enemies and regain Resolve. Strikes restore Resolve, so staying aggressive is part of staying alive.

- **Hollows** rush the pilgrim with a quick lunge.
- **Bellbearers** wind up a heavy close-range slam.
- **Cantors** retreat and mark the ground before calling down an area burst.
- **The Prior of Silence** appears every fourth sanctum and fires a radial volley.

Clear the room to choose one of three relics. Relics create trade-offs and build synergies across damage, recovery, critical hits, defense, reach, burn, and movement. Ash drops from defeated enemies and can be gathered during the fight.

## Technical notes

The game is a single static HTML file using Canvas 2D, Pointer Events, localStorage, and a time-based animation loop. It uses procedural visuals and requires no external game assets or runtime dependencies. A web font is requested for typography; system fallbacks are provided.
