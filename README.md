# cs-50x-scratch-tictactoe

### CS50x — Problem Set 0: Scratch


## Description

This is a two-player Tic-Tac-Toe game built in Scratch as part of Harvard's CS50x Introduction to Computer Science course. Player 1 plays as **X** and Player 2 plays as **O**. Players take turns clicking empty squares on a 3x3 grid to place their mark. The game automatically detects a winner across all rows, columns, and diagonals, announces the result, and resets for a new game. If all 9 squares are filled with no winner, the game declares a draw.


## How to Play

1. Click the **green flag** to start the game
2. The host character will welcome you and announce that **X goes first**
3. **Player 1 (X)** clicks any empty square to place their mark
4. **Player 2 (O)** then clicks any empty square to place their mark
5. Players alternate turns until someone gets **3 in a row** or the board is full
6. The game announces the winner and automatically resets for a new round

> No keyboard input required — just use your **mouse** to click the squares!



## Features

- Two-player gameplay on the same computer
- Automatic win detection for all 8 winning combinations (rows, columns, diagonals)
- Draw detection when all 9 squares are filled
- Animated host character that reacts to wins and draws
- Automatic game reset after each round
- Turn and move counter displayed on screen



## CS50 Requirements Met

| Requirement | Implementation |
|---|---|
| 2+ sprites | Host sprite + 9 square sprites |
| At least one non-cat sprite | Host character sprite |
| 3+ scripts | Multiple scripts across all sprites and stage |
| Conditional | `if/else` blocks for turn checking and win detection |
| Loop | `repeat until` loop on the Stage |
| Variable | `turn`, `moves`, `winner`, `s1`–`s9` |
| Custom block with input | `announce winner (player)` block |



## Project Structure

- **Stage** — initializes all variables and handles game reset
- **Host Sprite** — announces turns, checks all 8 winning combinations, declares winner or draw
- **Square Sprites (1–9)** — handle player clicks, update costumes and variables, broadcast game events
- **Project link** - https://scratch.mit.edu/projects/1288397875

## Built With

- [Scratch](https://scratch.mit.edu) — MIT's visual programming language


** License:** *Submitted as part of CS50x 2026 — Harvard University*
