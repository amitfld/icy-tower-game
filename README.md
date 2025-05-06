# ⚽ Messi Tower: Football-Themed Icy Tower Clone

Welcome to **Messi Tower**, a football-themed reimagination of the classic *Icy Tower* game. Built with **HTML, CSS, and JavaScript (Canvas API)**, this game blends platformer mechanics with rich football elements to create an addictive and fun experience.

[👉 Click here to play the game](https://tranquil-macaron-3f7912.netlify.app/)

---

## 🎮 Game Overview

In this game, you play as **Messi** trying to ascend an endless tower of platforms set in the iconic **Camp Nou Stadium**. The higher you climb, the greater your score. But beware—traps, enemies, and new surprises await as you aim for glory!

---

## 🚀 Features

### ✅ Core Features
- **Endless Platformer Gameplay:** Jump from platform to platform, climbing as high as possible.
- **Smooth Scrolling:** The screen scrolls upward dynamically as you progress.
- **Score System:** Points are awarded based on platforms climbed, rewarding faster ascents with more points.

### ⚠️ Platform Mechanics
- **Falling Platforms:** Platforms break and fall if you stand on them for more than 4 seconds.
- **Milestone Markers:** Every 10th platform displays its number for a milestone feel.
- **Wide Platforms:** ~33% of platforms are wider (120–200px) for varied gameplay.
- **Moving Platforms:** 6% of platforms move vertically within a 100px range.

### 👾 Enemies
- **Type 1 Enemy (Ronaldo):** Static enemy that kills you on contact.
- **Type 2 Enemy (Mbappé):** Patrols the platform, moving back and forth. Collision may trigger a **VAR review**.

### ⚽ Power-Ups & Items
- **Golden Boot Star:**
  - Appears on 7% of platforms.
  - Grants 7 seconds of invincibility + visual aura (7 footballs orbit Messi, one disappears each second).
- **Spring:**
  - Appears on 4% of platforms.
  - Boosts you with a high jump.
- **World Cup Trophy:**
  - Collectible item. Displayed in the top-right corner.
  - After collecting 3 trophies: Messi **transforms** into an *Argentina avatar* and **flies upwards** for 10 platforms, earning bonus score.
  - Trophy count resets after landing.

### 🟨 Yellow Card Debuff
- Stay too long (>3s) on a platform? You’ll receive a **Yellow Card** that **reduces movement speed & jump height** for 5 seconds.

### 🎥 VAR System
- colliding type 2 enemy (Mbappé) triggers a **VAR (Video Assistant Referee) review**.
- During review:
  - The game **pauses**.
  - A result is shown: ✅ Survived or ❌ Game Over.

### 🎶 Sound & Visuals
- **Background Music:** UEFA Champions League Anthem.
- **Sound Effects:**
  - Fly mode (Muchachos song)
  - Enemy hit (Ronaldo’s iconic *SIUUU*)
  - VAR review sound.
- **Custom Graphics:**
  - Messi (player)
  - Ronaldo & Mbappé (enemies)
  - Golden Boot, Trophy, Spring, Football (UI & powerups)
  - Camp Nou background.

### 🏆 Leaderboard
- On **game over**, the leaderboard displays the **top 10 scores** (stored locally).

### 🔄 Replayability
- **"Play Again" button:** Restart the game anytime after a game over.
- **Mute Button:** Toggle sound with 🔊/🔇.

---

## 🛠 Technologies

- **HTML + CSS**
- **JavaScript (Canvas API)**
- **LocalStorage (for leaderboard)**

---

## 📝 How to Play

- 🠔 **Left Arrow:** Move left.
- 🠖 **Right Arrow:** Move right.
- ␣ **Space Bar:** Jump.
- 🚫 **Avoid:** Enemies & falling off the screen.
- ⭐ **Collect:** Power-ups & trophies for bonuses.

---

## 📂 Assets

- Player: `messi_barca.png`, `messi_argentina.png`
- Enemies: `Ronaldo.png`, `mbappe.png`
- Background: `camp_nou.png`
- Powerups: `golden_boot.png`, `springboard.png`, `world_cup.png`
- Aura: `football.png`
- VAR Image: `var.png`
- Audio: `UEFA_Champions_League_Anthem.mp3`, `RONALDO_SIÙUUUUUU.mp3`, `Muchachos.mp3`, `var_sound.mp3`

---

## 📈 How Scoring Works

| Event                         | Points          |
|-------------------------------|-----------------|
| Land on higher platform       | +30 (per 100px) |
| Flying mode                   | +2 per frame    |


---

## 📜 Acknowledgments

- Project inspired by the **Icy Tower** classic game.
- Football-themed assets and sounds sourced & adapted for educational purposes.
- Developed as part of the university course: *Idea to Reality (March 2025)*.

⚠️ Note: Some football-themed assets (player avatars, audio clips, images) used in this project are the intellectual property of their respective owners. These assets were included **strictly for educational and non-commercial purposes** as part of a university assignment. If you are the rights holder and have concerns, please contact me.


---

## 👤 Author

Made with ❤️ for the **"Idea to Reality" 2025 course.**

GitHub: [@amitfld](https://github.com/amitfld)

LinkdIn: [Amit Feldman](https://www.linkedin.com/in/amit-fld/)

---
