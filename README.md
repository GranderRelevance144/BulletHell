# Bullet Hell

A fast-paced HTML5 Canvas bullet hell game featuring challenging boss fights, multiple playable classes, permanent progression, endless mode, dynamic difficulty, and a complete save system.

---

# Features

- 10 unique boss fights
- Multiple playable classes
- Campaign Mode
- Endless Mode
- Shop & permanent upgrades
- Coins and progression
- Dynamic difficulty director
- Bullet hell combat
- Boss phase transitions
- Particle effects
- Camera shake
- Hit stop
- Screen effects
- Accessibility options
- Save & Load
- Full audio system
- Performance overlay
- Object pooling
- Render pipeline

---

# Controls

| Action | Key |
|---------|-----|
| Move | WASD |
| Shoot | Left Mouse Button |
| Aim | Mouse |
| Dash (if available) | Space |
| Pause | ESC |
| Confirm | Enter |
| Back | Backspace |

---

# Installation

## Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/BulletHell.git
```

Open the project folder.

---

## Run

The easiest method is using **VS Code Live Server**.

Open:

```
index.html
```

using Live Server.

Alternatively, use any local HTTP server.

---

# Folder Structure

```text
BulletHell/

index.html
style.css
README.md
LICENSE
.gitignore

assets/

    music/
    sounds/
    sprites/
    fonts/

js/

    utils.js
    engine.js
    game.js
    input.js
    save.js
    audio.js
    camera.js
    player.js
    bullets.js
    particles.js
    enemies.js
    bosses.js
    powerups.js
    classes.js
    shop.js
    endless.js
    menus.js
    director.js
```

---

# Gameplay

Fight through increasingly difficult bosses.

Defeat enemies to earn coins.

Spend coins inside the shop to permanently improve your character.

Unlock new classes.

Master increasingly difficult attack patterns.

Try to survive forever inside Endless Mode.

---

# Player Classes

- Soldier
- Sniper
- Tank
- Engineer
- Mage

Each class has different stats, abilities and playstyles.

---

# Bosses

The campaign contains ten handcrafted bosses.

Every boss features:

- Multiple attack phases
- Unique projectile patterns
- Theme music
- Arena colors
- Custom visual effects

---

# Accessibility

Includes support for:

- Reduced Motion
- Reduced Particles
- High Contrast Mode
- Colorblind Modes
- Adjustable Bullet Opacity
- UI Scaling
- Screen Shake Toggle
- Large Cursor
- Visible Player Hitbox

---

# Performance

The engine includes:

- Object pooling
- Spatial collision grid
- View culling
- Fixed timestep simulation
- Render batching
- Performance overlay
- Automatic quality scaling

Designed for large numbers of simultaneous bullets.

---

# Saving

Progress is stored locally using browser storage.

Saved information includes:

- Coins
- Unlocks
- Upgrades
- Statistics
- Settings
- Best Endless Run

---

# Development

The project is written using:

- HTML5
- CSS3
- JavaScript (ES6)
- HTML5 Canvas

No external libraries are required.

---

# Assets

This repository contains the source code.

Audio, music, sprites and fonts should be placed inside the `assets` directory.

```
assets/

music/
sounds/
sprites/
fonts/
```

---

# Contributing

Issues and pull requests are welcome.

Please keep the coding style consistent with the existing project.

---

# License

This project is released under the MIT License.

See the LICENSE file for details.

---

# Credits

Programming

- VOID Nothingness
- ChatGPT (OpenAI) — development assistance

---

# Version

Current Version

```
v1.0.0
```

Initial public release.