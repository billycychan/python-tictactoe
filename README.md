# Tic-Tac-Toe Game

This is a simple Tic-Tac-Toe game implemented in Python using the tkinter library for the GUI. The game allows two players to take turns marking the spaces in a 3x3 grid to try and get three of their marks in a row, column, or diagonal.

![Python Tic Tac Toe Demo](/assets/screenshot.gif)

## How to Play

1. Run the Python script to start the game.
2. The game will randomly select a player to start.
3. Click on an empty space in the grid to place your mark (X or O).
4. Players take turns until one player wins by getting three of their marks in a row, column, or diagonal, or if the game ends in a tie.
5. Click the "restart" button to start a new game.

## Features

- Randomly selects the starting player.
- Highlights the winning row, column, or diagonal in green when a player wins.
- Highlights all cells in yellow when the game ends in a tie.
- Allows for an unlimited number of games without needing to restart the application.

## Code Structure

The game logic is implemented in a Python script using functions and the tkinter library for the graphical interface. Here's a brief overview of the key functions:

- `next_turn(row, column)`: Handles the logic for each player's turn, checking for a winner or a tie after each move.
- `check_winner()`: Checks the game board for a winning condition.
- `empty_spaces()`: Checks if there are any empty spaces left on the game board.
- `new_game()`: Resets the game board and selects a new starting player for a new game.

## Dependencies

This project requires Python 3.x and the tkinter library, which is included in standard Python installations.

## Usage

1. Clone or download the project files.
2. Run the `tictactoe.py` file using Python: `python tictactoe.py`.
3. Follow the on-screen instructions to play the game.

## Contribution

Contributions to improve the game or add new features are welcome. Feel free to submit a pull request or open an issue on GitHub.

Enjoy playing Tic-Tac-Toe!
