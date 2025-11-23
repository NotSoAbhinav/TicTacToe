<h1 align="center">TicTacToe</h1>


## Overview

This is a simple console-based Tic Tac Toe game written in Python.Despite its simplicity, it includes a functional Minimax AI, making the computer extremely difficult to beat. The game is fully terminal-based and uses number inputs (1–9) to place moves. (Later Added GUI interface also with name main_gui.py for better User Experience.)

## Features

* Play against a Minimax-powered AI
* Terminal/console based gameplay
* AI always plays optimally
* Input validation for invalid or occupied positions
* Win, loss, and draw detection

## Technologies/Tools Used

* Python 3.x
* Standard Python library only (no external packages)
* Terminal/Console interface

## Steps to Install & Run the Project

1. Install Python 3 from: [https://www.python.org/downloads/]
2. Download or clone the repository:

   ```
   git clone https://github.com/NotSoAbhinav/TicTacToe.git
   ```
3. Navigate to the project directory:

   ```
   cd TicTacToe
   ```
4. Run the game:

   ```
   python main.py
   ```

## Instructions for Testing

1. When prompted, choose a board position (1–9) to place your move.
2. AI will automatically respond with an optimal move.
3. Test the following:

   * Winning scenarios
   * Forcing a draw
   * Inputting invalid numbers
   * Trying an occupied position
   * Quitting using `q`
4. The game ends when:

   * Either player wins
   * The board is full (draw)
   * You choose to quit