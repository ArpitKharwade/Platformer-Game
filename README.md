# 🐉 Dragon Tower: Platformer Game using SFML

This is a 2D platformer developed in **C++** using the **SFML API**. The game is designed to run smoothly at **60 FPS** by efficiently managing the game loop and inputs.

## 🎮 Controls

- ⬅️➡️ : Move left/right  
- ⬆️⬇️ : Interact with objects (chests, keys, doors, coins), move on ladders/ropes  
- 🔼 Spacebar : Jump  
- 🅰️ A : Stop audio  
- 🔄 R : Reset dragons' positions (collected items like keys remain unchanged)  
- 💀 H : Enable Hardcore mode  
- ❌ Escape : Exit the game  

## 🏆 Game Objective

- 🐲 Your four dragons — **Yellow, Green, Blue, and Red** — have been imprisoned by the evil wizard .
- 🧙 They must climb the tower together to escape his clutches.
- 🔗 Due to the **dragon's pact**, they move as one — when one dragon moves, all others follow.
- 🗝️ Each dragon must:
  - Open a **chest** to release a key
  - Collect the **key**
  - Unlock the **door** on their side
- 🚪 Once all doors are open, the level is complete!

## ⚙️ Technical Details

- 💻 Written in **C++**
- 🎨 Uses **SFML** for graphics, audio, and input
- ⏱️ Maintains a stable **60 FPS** using a custom game loop
- 🎮 Smooth character control and interaction logic

## ✨ Features

- 🧠 Synchronized multi-character control
- 🧩 Puzzle-based level design
- 🎵 Audio management
- 🔥 Hardcore mode for added challenge
- 🎯 Responsive gameplay mechanics

## 🚀 Getting Started

### 📦 Prerequisites

- 🛠️ C++17 or later
- 📚 [SFML 2.5+](https://www.sfml-dev.org/download.php)

### 🧪 Build Instructions

1. 📥 Clone the repository:
   ```bash
   git clone https://github.com/yourusername/dragon-tower-platformer.git
   cd dragon-tower-platformer

