Tic-Tac-Toe Solver
Overview
This project implements a Tic-Tac-Toe game where a human player (Player O) plays against an AI player (Player X). The AI uses the Minimax algorithm to make optimal moves, ensuring the game is played efficiently. The human player provides input in terms of the row and column to place their move. The AI calculates the best possible move for each turn.

Features
Human vs AI: The game allows the human player (Player O) to play against the AI (Player X).
Minimax Algorithm: The AI uses the Minimax algorithm to evaluate all possible moves and make the best decision.
Board Validation: The game ensures that the human player's move is valid (the chosen cell must be empty).
Game End Conditions: The game checks for a win or a draw after each move and ends when one player wins or the board is full.
Requirements
Python 3.x (The game has been tested on Python 3.7+)
Installation
You don't need any additional libraries to run this project. Just make sure you have Python installed on your machine. If you don't have Python installed, you can download and install it from the official Python website.

Steps to Run the Game
Clone the repository (if applicable) or simply create a .py file and copy the code into it.
Open a terminal (or command prompt).
Navigate to the folder where the .py file is saved.
Run the game by typing:
nginx
Copy
python tic_tac_toe.py
How the Game Works
Initial Setup: The game starts with an empty 3x3 Tic-Tac-Toe board. The human player (Player O) goes first.
Human Move: The human player is asked to enter a row and column number (between 0 and 2) to place their 'O'.
AI Move: After the human player’s move, the AI (Player X) makes its move using the Minimax algorithm to determine the optimal move.
Game Check: After each move, the program checks for a winner or if the board is full (i.e., a draw).
End of Game: The game ends when:
One player wins (Player X or Player O).
The board is full and no player wins (a draw).
Gameplay Example
markdown
Copy
Welcome to Tic-Tac-Toe!
You are Player O and the AI is Player X.
X | O | X
---------
O | O | X
---------
X | X | O

Your turn (Player O):
Enter the row (0, 1, or 2): 1
Enter the column (0, 1, or 2): 0

X | O | X
---------
O | O | X
---------
X | X | O

AI (Player X) wins!
Game Rules
Tic-Tac-Toe Board: The game is played on a 3x3 grid, where two players take turns marking the empty cells with 'X' and 'O'.
Winning Conditions: A player wins if they have three of their marks in a row, either horizontally, vertically, or diagonally.
Draw: If all spaces are filled and no player has won, the game is a draw.
How to Play
The human player plays as Player O and the AI plays as Player X.
You will be prompted to enter the row and column numbers (from 0 to 2) where you'd like to place your move.
After you make your move, the AI will automatically make its move using the Minimax algorithm.
The game will end when there is a winner or the board is full (resulting in a draw).
Code Explanation
Minimax Algorithm: This is the core of the AI's decision-making process. The algorithm recursively explores all possible future moves and selects the one with the best score:

1: The AI wins.
-1: The human player wins.
0: The game is a draw.
Human Move Validation: Before each human move, the program checks that the entered row and column values are valid and that the chosen cell is empty.

Game State: The board is represented by a 3x3 list, and after each move, the state of the board is printed. The game continues until either the AI or the human player wins, or the board is full, resulting in a draw.

File Structure
bash
Copy
tic_tac_toe.py          # Main Python script to run the Tic-Tac-Toe game
README.md               # This README file
Credits
Author: Harshit Patel
Minimax Algorithm: The AI's optimal play is based on the Minimax algorithm.
Contact
If you have any questions or suggestions, feel free to reach out to [harshit972121@gmail.com].
