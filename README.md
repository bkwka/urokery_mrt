# Math Quest — HTML5 Math Game
Compete with aliens in interplanetary knight's tournament with equations from multiplication table and more

## 📘 Project Overview
**Math Quest** is a browser-based 2D pixel-art game where players solve multiplication problems to defeat monsters.  
The player competes against time, earns points, improves statistics, and can unlock advanced features through a personal account with payment integration.  
The game is built entirely on **HTML5**, using **JavaScript**, **Canvas API (or Phaser.js)**, and **Node.js** for backend.

---

## 🎯 Goal
Develop a complete HTML5 game with graphics, sound, personal accounts, statistics, and payment system.  
**GitHub Copilot** should generate all necessary code for this project based on this specification.

---

## ⚙️ Core Mechanics
- The player fights monsters by solving multiplication problems.  
- A correct answer deals damage to the monster. A wrong answer damages the player.
- Tournament divides on stages(1-6) and tiers(1-5) like stage_tier
- The game difficulty increase with each level.  
- Timer included.

---

## 🕹️ Gameplay
- **Game Elements:**  
  - Battle field (pixel-art scene)  
  - Math question panel (e.g. “7 × 8 = ?”)  
  - Input field for the answer  
  - Health bars for player and enemy  
  - Timer, score
  - Hero choosing

- **Game Modes:**  
  - Campaign with progressive levels  
  - Training mode (no monsters) if your hero have been defeated 

- **Progression System:**  
  - Enemies become stronger, means more complex math problems.  

---

## 🎨 Graphics
- 2D pixel-art style  
- Simple animations (movement, hits, flashes)  
- Assets stored in `/assets/graphics/`  
- Rendering via Canvas API or Phaser.js

---

## 🔊 Sound
- Sound effects: attack, mistake, victory, defeat  
- Background music 
- Volume controls and mute toggle in UI

---

## 🧭 User Interface
- **Main Menu:**  
  - "Start Game"   
  - "Statistics"  
  - "Profile"

- **In-game HUD:**  
  - Health bars(shields)
  - Timer  
  - Current question  

- **Results Screen:**  
  - Accuracy, progress  

---

## 📊 Saving & Statistics
- Progress saved locally or in a database  
- Track and display:  
  - Number of tiers passed 
  - Accuracy percentage  
  - Average reaction time  
  - Score and level  
- Statistics shown in user profile

---

## 👤 User Account
- Email + password authentication  
- Profile settings (name, avatar)  
- View personal stats and achievements  
- Manage subscription and payments  

---

## 💳 Payment System
- Stripe (or similar) integration  
- Some content locked for free users  
- Paid subscription unlocks full features  

---

## 🧱 Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript / Phaser.js  
- **Backend:** Node.js + Express  
- **Database:** MongoDB or PostgreSQL  

**Suggested folder structure:**
```
/src
  /game
    /scenes
    /entities
    /ui
  /assets
    /graphics
    /audio
  /server
    /routes
    /models
```

---

## 📱 Responsiveness
- Fully optimized for desktop, tablet and smartphone 
- Interface scales smoothly without losing readability  

---

## 🧩 Additional Notes
- 30 Enemies  
- Content (levels, monsters, etc.) should be configurable via JSON  
- Code must be modular and well-commented for Copilot  

---

## 💡 Hints for GitHub Copilot
- Implement main game logic in `/src/game/core.js`  
- Use `requestAnimationFrame` for the main loop  
- Follow MVC structure: separate logic, rendering, and UI  
- Create REST API for authentication and statistics  
- Add build and run instructions inside this README  

---

## 🧠 Concept & Creative Direction
**Maxim Demin** — Creative & Art Director  
