# 🧟 Zombie Shooter
A top-down survival zombie shooter game built with **Godot 4.4**. Fight off endless waves of zombies, collect health kits, and see how long you can survive as the horde grows ever larger.
![Godot Engine](https://img.shields.io/badge/Godot-4.4-blue?logo=godot-engine)
![Language](https://img.shields.io/badge/Language-GDScript-green)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS%20%7C%20Web-lightgrey)
---
## 🎮 Gameplay
- Move your character with **WASD**
- Aim with the **mouse cursor** and shoot with **left click**
- Survive increasingly frequent zombie waves
- Pick up **health kits** dropped by fallen enemies to stay alive
- The game ends when your health reaches zero — then it reloads and you try again!
### Controls
| Action | Input |
|--------|-------|
| Move Up | `W` |
| Move Down | `S` |
| Move Left | `A` |
| Move Right | `D` |
| Aim | Mouse cursor |
| Shoot | Left mouse button |
---
## ✨ Features
- **Top-down 2D gameplay** with smooth 8-directional movement
- **Enemy AI** using NavigationAgent2D pathfinding to chase the player
- **Progressive difficulty** — zombies spawn faster the longer you survive
- **Muzzle flash & recoil** visual effects for satisfying gunplay
- **Dynamic lighting** — atmospheric spotlight centered on the player
- **Health system** — take damage on zombie contact, restore health with kits
- **Sound effects** — gunshots, impacts, zombie growls, and ambient music
---
## 🚀 Getting Started
### Prerequisites
- [Godot Engine 4.4](https://godotengine.org/download) — no other dependencies required
### Running the Game
1. Clone or download this repository
   ```bash
   git clone https://github.com/VaibhavSoni24/Zombie-Shooter.git
   ```
2. Open **Godot 4.4** and choose **Open Project**
3. Navigate to the cloned folder and select `project.godot`
4. Press **F5** (or click the ▶ Play button) to start the game
### Building a Standalone Executable
1. In Godot, open **Project → Export**
2. Select your target platform (Windows, Linux, macOS, or Web)
3. Click **Export Project** and choose an output directory
4. Run the generated executable
---
## 🗂️ Project Structure
```
Zombie-Shooter/
├── scenes/          # Game scenes (.tscn)
│   ├── level.tscn       # Main level (entry point)
│   ├── Player.tscn      # Player character
│   ├── Enemy.tscn       # Zombie enemy
│   ├── Bullet.tscn      # Projectile
│   ├── HealthKit.tscn   # Health powerup
│   └── HUD.tscn         # Heads-up display
├── scripts/         # GDScript logic (.gd)
│   ├── Player.gd        # Movement, shooting, damage
│   ├── Enemy.gd         # AI pathfinding & behavior
│   ├── Level.gd         # Wave spawning & progression
│   ├── PlayerState.gd   # Global autoload (health, position)
│   └── ...
├── sprites/         # Sprite & texture assets
├── sounds/          # Audio files (.ogg)
└── project.godot    # Godot project configuration
```
---
## 🛠️ Development
- Scene files (`.tscn`) are edited in Godot's Scene editor
- Script files (`.gd`) can be edited in Godot's built-in script editor or any text editor
- The `.godot/` cache folder and `*.tmp` files are excluded via `.gitignore`
---
## 📄 License
This project is open source. Feel free to use, modify, and share it.
