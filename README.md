# 🕯️ Blind Pulse — A Light in the Darkness

An atmospheric 2D survival game where light is your guide, fog conceals danger, and every movement comes with a risk.

**Move to reveal the path. Stand still to reveal the Shadows.**

Blind Pulse is a browser-based survival game built with HTML5 Canvas, CSS3, and vanilla JavaScript. Navigate through a world consumed by darkness, collect fragments of a shattered lighthouse lens, defeat powerful bosses, and restore the light that guides lost ships home.

## 🌑 The Story

Long ago, the Lighthouse of Silence guided ships safely through the darkest storms. Its light was a promise that even the most distant traveler could find their way home.

Then the Abyss awakened beneath the sea.

An ancient darkness released a dense fog that extinguished the lighthouse and shattered its lens. The fragments scattered throughout the Abyss, and the lighthouse keeper vanished into the darkness. Only one spark remained.

**You are that spark.**

Your journey leads through mist-covered shores, abandoned harbors, frozen waters, haunted cliffs, and the heart of the Abyss itself.

But the fog hides more than lost fragments. Shadows wait within it, and the Hounds of the Abyss can follow the slightest disturbance.

Collect the fragments. Restore the lens. Bring the light back to the world.

## 🎮 Core Gameplay

Blind Pulse revolves around a simple but dangerous mechanic: **movement changes what you can see.**

- **Move to discover.** Your movement stirs the fog and reveals glowing light fragments.
- **Stand still to observe.** As the fog settles, hidden Shadows become easier to see.
- **Watch your surroundings.** Hostile creatures move through the darkness, and some become more dangerous when you stop.
- **Collect fragments.** Complete objectives to progress through each stage.
- **Adapt to survive.** Each level introduces different challenges, from timed survival to boss encounters.

You cannot rely on constant movement or complete stillness. Survival requires learning when to move and when to stop.

## ✨ Features

- **25 progression levels** with varied objectives and increasing difficulty.
- **5 boss encounters** that challenge your movement and survival skills.
- **Three-star level ratings** based on your performance.
- **Multiple objective types:** collecting fragments, surviving until dawn, maintaining silence, lighting beacons, staying in motion, avoiding damage, and completing timed challenges.
- **Three starting hearts** and a health system with temporary invulnerability after taking damage.
- **Collectible power-ups:** protective shields, extra hearts, and healing.
- **Atmospheric visuals** featuring animated fog, dynamic lighting, glowing particles, and a minimalist dark environment.
- **Procedural sound effects and ambient music** generated with the Web Audio API.
- **Four interface languages:** English, Russian, Ukrainian, and Polish.
- **Progress persistence** using browser local storage, including unlocked levels, star ratings, and personal records.
- **Responsive canvas rendering** designed to adapt to different screen sizes.

## 🗺️ The Journey — 25 Levels

The journey through the Abyss consists of five groups of increasingly dangerous challenges.

| # | Level | Objective |
|---:|---|---|
| 1 | The Shore | Collect the first light fragments. |
| 2 | Foggy Harbor | Evade creatures drawn to the fog. |
| 3 | Night Watch | Survive until dawn. |
| 4 | Echo Gorge | Navigate a dangerous, echoing darkness. |
| 5 | Mistress of the Cove | Face the first boss. |
| 6 | Beacon Lights | Ignite the scattered beacons. |
| 7 | Noisy Forest | Keep moving to awaken the sleeping light. |
| 8 | Ice Hole | Collect fragments without taking damage. |
| 9 | Long Night | Endure a prolonged night. |
| 10 | Ghost Captain | Confront a spectral boss. |
| 11 | Ringing Cliffs | Keep moving through the ringing rocks. |
| 12 | Dead Calm | Accumulate enough time in silence. |
| 13 | Black Tide | Collect fragments before time runs out. |
| 14 | Last Dawn | Survive the final stretch of darkness. |
| 15 | Warden of the Abyss | Defeat the guardian of the Abyss. |
| 16 | Path of Shadows | Collect fragments without taking damage. |
| 17 | Race the Tide | Gather fragments before the tide catches you. |
| 18 | Mirror Ice | Maintain complete stillness for long enough. |
| 19 | Burning Shore | Ignite a series of beacons. |
| 20 | Lord of Echoes | Challenge another powerful boss. |
| 21 | Deadfall | Keep moving to clear the path. |
| 22 | Endless Night | Survive an extended period of darkness. |
| 23 | Deep Lights | Ignite the beacons hidden in the depths. |
| 24 | Final Breath | Collect fragments before time expires. |
| 25 | Heart of the Abyss | Face the final boss and complete the journey. |

Each level has its own objective, atmosphere, and difficulty. Completing stages unlocks further progress, while earning stars rewards skilled survival.

## 🕹️ Controls

Blind Pulse uses pointer-based movement.

| Input | Action |
|---|---|
| Move the mouse | Guide the spark toward the cursor. |
| Stop moving the mouse | Let the fog settle and reveal nearby threats. |
| Click or tap | Start, advance through the introduction, continue, retry, or interact with menus. |

There is no conventional combat system. You survive through movement, observation, timing, and careful navigation.

## ❤️ Survival System

You begin each run with **three hearts**.

Colliding with a hostile creature costs one heart. After taking damage, a short period of temporary invulnerability gives you an opportunity to escape.

During your journey, you can find three types of power-ups:

- **Light Shield** — Absorbs the next damaging collision.
- **Extra Heart** — Increases maximum health and restores one heart.
- **Healing Light** — Restores health to its maximum.

Some challenges require you to avoid every hit, while others test how long you can survive under pressure.

Lose all your hearts, and the darkness closes in. You can retry and continue learning from each attempt.

## 🌌 Visuals and Sound

Blind Pulse uses a minimalist visual style built around contrast, visibility, and atmosphere.

- Deep black and midnight-blue environments.
- Dense, animated fog that changes with player movement.
- A small golden-white spark representing the player.
- Crimson hostile entities emerging from the darkness.
- Turquoise light fragments glowing through the mist.
- Atmospheric particles, gradients, and radial lighting.
- Procedurally generated ambient music and sound effects.

The visual design keeps the world deliberately obscured. What you cannot see is often more dangerous than what you can.

## 🏁 The Goal

Collect the fragments of the shattered lens, overcome the guardians of the Abyss, and restore the Lighthouse of Silence.

The final outcome reflects your journey, including your survival performance and the number of times your light has gone out.

**The darkness may extinguish the spark. It cannot stop it from burning again.**

## 🛠️ Built With

- **HTML5** — Game structure and canvas element.
- **CSS3** — Full-screen presentation and layout.
- **JavaScript** — Game logic, enemy behavior, progression, and rendering.
- **HTML Canvas API** — Real-time graphics, fog, particles, lighting, and animation.
- **Web Audio API** — Procedurally generated music and sound effects.
- **Browser Local Storage** — Persistent progress, unlocked levels, settings, and records.

The game uses vanilla JavaScript and requires no external game engine or third-party framework.

## 🚀 How to Run

1. Clone or download this repository.
2. Open the game's HTML file in a modern web browser.
3. Click or tap to begin your journey.

No build tools, package installation, or server setup are required for basic local play.

You can also play the game online:

**[Play Blind Pulse on GitHub Pages](https://mpmotorobot.github.io/Blind-Pulse-game-/)**

## 📌 Project Status

Blind Pulse is a playable browser-based game featuring its core movement mechanic, animated environment, enemy AI, boss encounters, 25-level progression, survival system, audio, multilingual interface, and ending.

The project is built as a standalone web game and can be launched directly in a modern browser.

## 👤 Author

**Yevhenii Yelisieiev — YuJenix**

- **GitHub:** [@mpmotorobot](https://github.com/mpmotorobot)
- **Telegram:** [@YuJenix](https://t.me/YuJenix)
- **Portfolio:** [mpmotorobot.github.io](https://mpmotorobot.github.io)

© 2026 Blind Pulse. All rights reserved.

---

*Blind Pulse — Find the light. Respect the silence. Survive the Abyss.*
