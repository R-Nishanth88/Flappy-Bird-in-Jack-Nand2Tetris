# Flappy Bird in Jack (Nand2Tetris)

This project is a recreation of the classic **Flappy Bird** game, fully implemented in the **Jack programming language** as part of the [Nand2Tetris](https://www.nand2tetris.org/) course. It demonstrates object-oriented design, simple physics, and game logic within the limitations of the Hack platform.

## 🎮 Features

- Side-scrolling pipes with random gaps
- Gravity and flap mechanics
- Collision detection
- Score tracking system

## 📁 Project Structure

- `Main.jack` / `Main.vm`: Entry point of the game.
- `FlappyBird.jack` / `FlappyBird.vm`: Controls bird movement and logic.
- `Pipe.jack` / `Pipe.vm`: Pipe generation and movement logic.
- `Scoreboard.jack` / `Scoreboard.vm`: Score calculation and display.
- `MyMath.jack` / `MyMath.vm`: Utility functions (e.g., random number generation).
- `FlappyBirdGame.jack` / `FlappyBirdGame.vm`: Orchestrates game mechanics and rendering.

## 🛠 How to Run

1. Open the Nand2Tetris **VM Emulator**.
2. Load all `.vm` files from the project folder.
3. Start execution from `Main.vm`.
4. Use the keyboard input (usually space or up arrow) to make the bird flap.

> 💡 Make sure you have the full Nand2Tetris toolset installed.

## 📚 Requirements

- Nand2Tetris Software Suite (Version 2.5 or above recommended)
- Basic understanding of Jack and the Hack platform

## 📦 Compilation

To recompile the `.jack` files into `.vm` files:

```bash
JackCompiler path/to/FlappyBird\ Final
