# 🐍 Retro Snake Game (Raylib + C++)

A modern **Snake Game** built using **C++** and the Raylib library.  
This version uses **OOP concepts**, **deque data structure**, and smooth rendering with sound effects for an engaging retro experience.

---

## 🎮 Features

- 🧱 Object-Oriented Design (Snake, Food, Game classes)
- 🔁 Smooth movement using time-based updates
- 🍎 Random food spawning (avoids snake body)
- 🔊 Sound effects (eat & game over)
- 📈 Score & High Score tracking
- 🎨 Clean retro UI with custom colors
- 🐍 Snake grows dynamically using `deque`

---

## 🛠️ Technologies Used

- C++
- Raylib
- Deque (STL)
- Raymath (Vector operations)

---

## ▶️ How to Run

### 1. Install Raylib  
Visit: https://www.raylib.com/

### 2. Compile the Code  

```bash
g++ main.cpp -o snake -lraylib -lopengl32 -lgdi32 -lwinmm
