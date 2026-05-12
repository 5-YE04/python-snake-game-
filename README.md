# Snake Game 🐍

A classic Snake game built with Pygame. Control the snake, eat food to grow, and avoid colliding with walls or yourself.

## Features
- Smooth keyboard controls (arrow keys)
- Score display
- Game over screen with option to replay (C) or quit (Q)
- Increasing length as you eat food

## Requirements
- Python 3.7+
- Pygame

Install Pygame:
bash
pip install pygame

Run the game:
bash
python snake_game.py

How to Play
Use arrow keys (← ↑ → ↓) to move the snake.
Eat the green food blocks to grow longer and increase your score.
Avoid hitting the walls or your own tail.
Press C after game over to play again, or Q to quit.
Controls


KeyAction←Move left→Move right↑Move up↓Move downCRestart after game overQQuit after game over
Customization
You can modify the following constants in snake_game.py:
snake_speed – game speed (default 15)
dis_width / dis_height – window size (default 600x400)
snake_block – size of snake and food blocks (default 10)
