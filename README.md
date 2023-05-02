# Tic Tac Toe using Minmax

Tic Tac Toe AI
This is a simple Tic Tac Toe game with an AI opponent that uses the minimax algorithm to select the best move.

## Getting Started
To play the game, simply run the play_game() function from the command line:<br>
Copy code python tic_tac_toe.py<br>
The game will start, and you will be prompted to choose whether you want to go first or let the AI go first.

How to Play
The game is played on a 3x3 grid. You are the 'O' player and the AI is the 'X' player.<br>
The goal is to get three in a row - horizontally, vertically or diagonally.

To make a move, enter a number between 0 and 8, where 0 is the top left corner, and 8 is the bottom right corner, like so:

 0 | 1 | 2 <br>
---+---+---<br>
 3 | 4 | 5 <br>
---+---+---<br>
 6 | 7 | 8 <br>
Enter move (0-8):<br>

If the cell you choose is already taken or you enter an invalid move, you will be prompted to try again.

## Algorithm <br>
The AI opponent uses the minimax algorithm to select the best move. The minimax algorithm is a recursive algorithm that explores all possible future moves to find the best move for the current player.

## Future Improvements
The game could be improved in several ways, such as:<br>
Adding a graphical user interface.<br>
Implementing other AI algorithms, such as the Monte Carlo Tree Search algorithm.<br>
Adding different difficulty levels to the AI opponent.<br>
