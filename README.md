# MySnakeGame

![C++](https://img.shields.io/badge/Language-C++-blue) ![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)

A terminal-based **Snake Game** built in C++ with a custom queue-based snake body, random fruit generation, and smooth movement. I wrote my own version based on the classic game.  

## Game Preview

| Game Start | Game Over |
|:----------:|:---------:|
| ![Start](Game%20begins.png) | ![Over](Game%20over.png) |


---
## Features
- Smooth ASCII-based snake movement  
- Random fruit spawning  
- Collision detection with walls and snake body  
- Adjustable speed and starting length  
- Score tracking  
- Runs directly in Windows CMD


---
## Structure
MySnakeGame\
│── SnakeGame.cpp # Main game logic, input handling, rendering \
│── Snake.cpp # Custom queue class for snake body \
|── README.md # Project documentation


---

## To Run

### Step 1: Install a C++ Compiler
You need **g++** on Windows. Recommended options:

- MinGW-w64
- TDM-GCC  
- MSYS2  

---

### Step 2: Navigate to Project Folder
- Open **Command Prompt** and go to your project folder. 

---

### Step 3: Compile the Project

```bash
g++ -std=c++17 SnakeGame.cpp Snake.cpp -o MySnakeGame.exe
```


---

### Step 4: Run
- MySnakeGame.exe
