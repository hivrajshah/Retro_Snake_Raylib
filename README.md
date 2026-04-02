# 🐍 Retro Snake Game

A classic, fully functional Retro Snake game built using **C++** and the **raylib** library. Guide the snake to eat the food, grow longer, and compete for the highest score without crashing into the walls or yourself!

## ✨ Features
* **Classic Grid-Based Movement:** Smooth, interval-based updates for authentic retro gameplay.
* **Score & High Score Tracking:** Keeps track of your current score and your highest score across sessions.
* **Audio Effects:** Includes sound effects for eating food and game over events.
* **Dynamic Rendering:** Custom colors, rounded snake segments, and image-based food textures.

---

## 🎮 How to Play

**Objective:** Eat as much food as possible to grow your snake and increase your score. The game ends if you hit the screen borders or your own tail.

### Controls:
* **`W`** - Move Up
* **`S`** - Move Down
* **`A`** - Move Left
* **`D`** - Move Right
* *Note: Pressing any movement key after a Game Over will instantly restart the game.*

---

## 🛠️ Prerequisites & Setup

To compile and run this game on your local machine, you will need:

1. A **C++ Compiler** (like GCC, Clang, or MSVC).
2. The **[raylib library](https://www.raylib.com/)** installed and configured for your environment.

### Project Structure
Make sure your project directory looks like this before running, as the code relies on external graphics and sound assets:

```text
├── main.cpp          # The main source code file
├── Graphics/
│   └── food.png      # Texture for the snake food
└── Sound/
    ├── eat.mp3       # Sound played when food is eaten
    └── fail.mp3      # Sound played on Game Over
