Tic-Tac-Toe Game in C++

Overview
A complete implementation of the classic Tic-Tac-Toe game written in C++ that runs in the terminal. This project demonstrates fundamental programming concepts including 2D arrays, input validation, and game state management.

Features
✔ Two-player mode - Play against a friend locally
✔ Interactive terminal UI - Clean ASCII art board display
✔ Input validation - Prevents invalid moves
✔ Win detection - Automatically checks all winning conditions
✔ Draw detection - Identifies when the game ends in a tie
✔ Turn management - Alternates between X and O players

Installation

Clone the repository:

bash
git clone https://github.com/your-username/OSTLAB1-TicTacToe.git
cd OSTLAB1-TicTacToe

Compile the program:

bash
g++ tictactoe.cpp -o tictactoe

Run the game:

bash
./tictactoe

How to Play
The game board is displayed with numbered positions (1-9):

text
 1 | 2 | 3
---+---+---
 4 | 5 | 6
---+---+---
 7 | 8 | 9

Players take turns entering a number (1-9) to place their symbol (X or O)

The game automatically:

Validates moves (prevents overwriting)
Checks for wins (rows, columns, diagonals)
Declares a draw when the board is full

Game Rules
Player X always goes first
Players alternate placing their symbols
First to get 3 in a row (horizontally, vertically, or diagonally) wins
Game ends in a draw if all spaces are filled without a winner

Code Structure
plaintext
.
├── tictactoe.cpp      # Main game logic and interface
├── README.md          # This documentation file
├── screenshot.png     # Game screenshot
└── LICENSE            # MIT License file

Key Functions:
displayBoard() - Renders the current game state
makeMove() - Handles player moves
checkWin() - Determines if a player has won
checkDraw() - Checks for tied game

Dependencies
C++11 or later
Standard C++ libraries
GNU GCC or compatible compiler

Future Enhancements
Single-player vs AI mode
Difficulty levels (Easy/Medium/Hard)
Score tracking across multiple games
Colorized terminal output
Network multiplayer support

Contributing
Contributions are welcome! Please follow these steps:
Fork the repository
Create a new branch (git checkout -b feature/improvement)
Commit your changes (git commit -m 'Add new feature')
Push to the branch (git push origin feature/improvement)
Open a Pull Request