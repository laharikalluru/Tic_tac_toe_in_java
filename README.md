# Tic Tac Toe Game in Java
This is a simple command-line based 3x3 Tic Tac Toe game implemented in Java. Two players take turns to place their marks (X and O) on the board, and the game checks for a winner or a draw after every move.

# Features

* Interactive console-based gameplay

* Input validation (only numbers 1-9 accepted, no overwriting taken slots)

* Real-time board display after each move

* Automatic winner detection or draw detection

* Clear instructions and error handling for invalid inputs

# How to Play

Run the program.

Player X always starts first.

Enter a slot number (1 to 9) to place your mark.

The board positions are numbered as follows:

```
|---|---|---|
| 1 | 2 | 3 |
|-----------|
| 4 | 5 | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
```

* The game ends when a player wins by placing three of their marks in a horizontal, vertical, or diagonal row, or if all slots are filled resulting in a draw.


# How to Run

* Make sure you have Java JDK installed.

* Clone this repository or download the source file Tic_Tac_Toe.java.

* Open a terminal/command prompt.

# Compile the Java file:
  
javac Tic_Tac_Toe.java

# Run the program:

java Tic_Tac_Toe

# Code Overview

* board: An array representing the 3x3 board slots.

* turn: Tracks the current player ("X" or "O").

* checkWinner(): Checks all winning conditions and determines if there's a winner or a draw.

* printBoard(): Prints the current state of the board.

* Input handling uses Scanner with validation to prevent invalid or duplicate moves.

Welcome to 3x3 tic tac toe.
```
|---|---|---|
| 1 | 2 | 3 |
|-----------|
| 4 | 5 | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
```
X will play first. Enter a slot number to place X in:
3
```
|---|---|---|
| 1 | 2 | X |
|-----------|
| 4 | 5 | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
```
O's turn; enter a slot number to place Oin:
5
```
|---|---|---|
| 1 | 2 | X |
|-----------|
| 4 | O | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
```
X's turn; enter a slot number to place Xin:
2
```
|---|---|---|
| 1 | X | X |
|-----------|
| 4 | O | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
```
O's turn; enter a slot number to place Oin:
1
```
|---|---|---|
| O | X | X |
|-----------|
| 4 | O | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
```
X's turn; enter a slot number to place Xin:
6
```
|---|---|---|
| O | X | X |
|-----------|
| 4 | O | X |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
```
O's turn; enter a slot number to place Oin:
9
```
|---|---|---|
| O | X | X |
|-----------|
| 4 | O | X |
|-----------|
| 7 | 8 | O |
|---|---|---|
```
Congratulations! O's have won! Thanks for playing.

# License
This project is open source and free to use.
