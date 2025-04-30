# 🐍 Snake-Water-Gun Game in Python

This is a Python implementation of the classic **Snake-Water-Gun** game — a fun variation of Rock-Paper-Scissors! You play against the computer, which makes its move randomly.

## 🎮 How to Play

- Choose one of the three options:
  - **s** for Snake
  - **w** for Water
  - **g** for Gun
- The computer also makes a random choice.
- Game rules:
  - Snake drinks water → Snake wins
  - Water disables gun → Water wins
  - Gun shoots snake → Gun wins
- Same choice → It's a tie

## 🧠 Logic

The game logic is implemented in the `gameWin()` function, which:
- Returns `None` for a tie
- Returns `True` if the player wins
- Returns `False` if the computer wins

## ▶️ How to Run

1. Make sure Python is installed (version 3.x).
2. Save the code in a file, e.g., `snake_water_gun.py`.
3. Run the game in terminal or command prompt:
   ```bash
   python snake_water_gun.py
