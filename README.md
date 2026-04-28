# 2nd-sem-finals-project


# ⭐ STAR RANGER – Boss Fight Bullet Hell Game

[![Play on GitHub Pages](https://img.shields.io/badge/Play%20Now-GitHub%20Pages-brightgreen?style=for-the-badge&logo=github)](https://miguelwalter.github.io/2nd-sem-finals-project/)
[![Status](https://img.shields.io/badge/status-live-success)](https://miguelwalter.github.io/2nd-sem-finals-project/)

> **Defeat enemies, survive bullet hell, and summon the VOID TITAN!**  
> A complete arcade-style space shooter with 5 enemy types, boss battles, and intense bullet patterns – **playable instantly in your browser**.

![Gameplay Screenshot](Screenshots/Game.png)

---

## 🎮 Play Now – No Installation Required

The game is hosted live on **GitHub Pages**. Open:  
🔗 **[https://MiguelWalter.github.io/STAR-RANGER/](https://miguelwalter.github.io/2nd-sem-finals-project/)**

- Works on desktop, tablet, and mobile browsers.
- No login, no download – just pure arcade action.

---

## 📖 Project Description

**STAR RANGER** is a browser-based bullet hell arcade game built with HTML, CSS, and JavaScript. You control a starship with a tiny hitbox, fighting through waves of unique enemies while dodging complex bullet patterns. Reach 500 points to summon the **VOID TITAN** boss for an epic final battle!

The game features:
- **5 unique enemy types** – Spiral (rotating bullet rings), Shield (needs 2 hits), Kamikaze (charges at you), Miner (drops healing orbs), Fast/Standard enemies
- **Epic boss fight** – 30 HP VOID TITAN with 4 different attack patterns and intense bullet hell mechanics
- **Smooth mouse controls** – Auto-firing laser with continuous shooting
- **Health system** – 3 hearts with invincibility frames after getting hit
- **Healing orbs** – Dropped by Miner enemies to restore health
- **High score tracking** – Saves your best score locally
- **Fully responsive** – Works on all screen sizes

This project demonstrates front-end game development, canvas rendering, collision detection, and state management.

---

## 🕹️ Controls & Gameplay

### Controls
- **Mouse Movement** – Move your ship anywhere on screen (tiny hitbox for precise dodging)
- **Auto-fire** – Continuous laser shooting (no clicking needed!)

### Enemies
| Enemy Type | HP | Behavior |
|------------|----|-----------| 
| 🌀 Spiral | 1 | Shoots rotating bullet rings |
| 🛡️ Shield | 2 | Requires 2 hits, shoots aimed+spread patterns |
| 💥 Kamikaze | 1 | Charges directly at your ship |
| ⛏️ Miner | 1 | Drops ❤️ healing orb when defeated |
| ⚔ Normal/Fast | 1 | Standard enemies with different speeds |

### Boss Fight – VOID TITAN
- **Spawns at 500 points** – No other enemies appear during boss fight
- **30 HP** – Requires sustained firepower
- **4 attack patterns**:
  - Radial burst (16-direction spread)
  - Aimed + spread (targets your position)
  - Spiral rings (rotating bullet walls)
  - Cross + diagonal (8-direction blast)
- **Enraged mode** (under 15 HP) – Extra bullet waves
- **Reward** – +100 bonus points on defeat!

### Goal
Survive enemy waves, reach 500 points, defeat the VOID TITAN, and achieve the highest score possible!

---

## 📸 Screenshots

> *Replace these placeholder paths with actual screenshots from your deployed game.*

| Main Menu | In-Game Action |
|-----------|----------------|
| ![Main Menu](Screenshots/Menu) | ![Gameplay](Screenshots/Game) |

| Boss Fight | Game Over |
|------------|-----------|
| ![Boss](Screenshots/Boss) | ![Game Over](Screenshots/GameOver) |

---

## 👥 Developer Team

| Role | Name | GitHub | Responsibilities |
|------|------|--------|------------------|
| Game Coder | **Uy, Miguel Walter P.** | [MiguelWalter](https://github.com/MiguelWalter) | Game architecture, enemy AI, boss mechanics, bullet patterns, collision detection, core game loop |
| Design Coder | **Nielmar Josh** | [NielmarJosh](https://github.com/NielmarJosh) | UI/UX design, visual effects, canvas rendering, animations, responsive layout |

---

## 🧰 Technologies Used

- **HTML5** – Structure and semantic layout
- **CSS3** – Responsive design, glass-morphism effects, flexbox/grid
- **JavaScript (ES6)** – Game state management, canvas rendering, event handling, collision detection
- **Canvas API** – Real-time 2D graphics for all game visuals
- **LocalStorage API** – High score persistence
- **GitHub Pages** – Hosting and deployment

---

## 🎯 Future Improvements

- [ ] Add power-ups (rapid fire, spread shot, shield)
- [ ] Multiple difficulty levels
- [ ] Sound effects and background music
- [ ] More boss phases and attack patterns
- [ ] Leaderboard system
- [ ] Mobile touch controls

---

## 📝 How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/MiguelWalter/STAR-RANGER.git
Navigate to the project folder:

bash
cd STAR-RANGER
Open index.html in your browser or use Live Server in VS Code

📄 License
This project was developed as an academic/portfolio assignment.

🙏 Acknowledgments
Inspired by classic arcade shooters like Galaga and Touhou Project

Built with vanilla JavaScript – no external game engines

⭐ If you enjoy the game, give it a star on GitHub! ⭐

text

Just copy everything inside this code block and save it as `README.md` in your project folder!
