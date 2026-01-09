# Emberfall

A tactical strategy game built entirely in a single HTML file. Command your warband through hex-based combat across multiple campaign missions.

![Emberfall](https://img.shields.io/badge/game-tactical%20strategy-orange)
![HTML5](https://img.shields.io/badge/HTML5-canvas-blue)
![No Dependencies](https://img.shields.io/badge/dependencies-none-green)

## Play

Simply open `index.html` in a modern web browser, or host it on any static file server.

```bash
# Quick start with Python
python3 -m http.server 8080
# Then open http://localhost:8080
```

## Features

### Units
| Unit | Role | HP | Attack | Defense | Range | Abilities |
|------|------|-----|--------|---------|-------|-----------|
| Warrior | Melee Fighter | 120 | 25 | 15 | 1 | Strike, Shield Bash |
| Archer | Ranged Attacker | 80 | 20 | 8 | 3 | Shoot, Piercing Shot |
| Mage | Spellcaster | 70 | 30 | 5 | 2 | Fireball, Frost Nova |
| Healer | Support | 75 | 10 | 10 | 1 | Heal, Blessing |
| Knight | Tank | 150 | 20 | 20 | 1 | Charge, Fortify |

### Abilities
- **Strike** - Powerful melee attack (1.2x damage)
- **Shield Bash** - Stuns enemy for one turn
- **Shoot** - Ranged attack (1.1x damage)
- **Piercing Shot** - Ignores 50% of enemy defense
- **Fireball** - Magical ranged attack (1.3x damage)
- **Frost Nova** - Damages target and adjacent enemies
- **Heal** - Restores 25 HP to ally
- **Blessing** - Increases ally's attack for 2 turns
- **Charge** - Rush to enemy and attack (1.3x damage)
- **Fortify** - Increases ally's defense for 2 turns

### Terrain
| Terrain | Movement Cost | Defense Bonus |
|---------|---------------|---------------|
| Plains | 1 | 0 |
| Forest | 2 | +3 |
| Hills | 2 | +5 |
| Mountains | Impassable | - |
| Water | Impassable | - |

### Game Modes
- **Campaign** - 5 missions with increasing difficulty and progression system
- **Skirmish** - Customizable battles with adjustable map size and enemy count

## Controls

- **Left Click** - Select unit, move, attack, use ability
- **Right Click + Drag** - Pan camera
- **Scroll Wheel** - Zoom in/out
- **End Turn** - Pass turn to enemy

## Tech Stack

- Pure HTML5 Canvas
- Vanilla JavaScript
- No external dependencies
- Single file (~2600 lines)

## License

MIT
