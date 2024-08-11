# tic-tac-toe-game
# Tic-Tac-Toe Game

This project involves developing a Tic-Tac-Toe game in C++. Traditionally played on paper, Tic-Tac-Toe is a simple yet engaging game for two players. In this project, we will implement a console-based C++ program that simulates the game, allowing players to interact using keyboard inputs.

## How to Play Tic-Tac-Toe

Here are the key rules for playing Tic-Tac-Toe:

- Players take turns placing their chosen letter, X or O, in an empty cell of a 3x3 grid.
- The game alternates between the two players until one wins or the game ends in a draw.
- A player wins by aligning three of their letters horizontally, vertically, or diagonally.
- The game is a draw if all cells are filled and no player has achieved the winning alignment.

## Features of the C++ Tic-Tac-Toe Game

This implementation includes the following features:

- A 3×3 grid to play the game.
- Two-player gameplay.
- Players can choose their marker: X or O.
- Turn-based play, alternating between players.

## Game Components

The game consists of the following components, utilizing various functions and data structures to facilitate gameplay:

1. **Game Board**

   The Tic-Tac-Toe board is represented by a 3x3 array initialized with empty spaces:

   ```cpp
   char board[3][3] = {{' ', ' ', ' '}, {' ', ' ', ' '}, {' ', ' ', ' '}};
