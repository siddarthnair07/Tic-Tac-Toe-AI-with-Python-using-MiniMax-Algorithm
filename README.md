# Tic Tac Toe AI with Python using Minimax Algorithm
This is a simple implementation of a Tic Tac Toe game with an AI opponent that uses the Minimax algorithm to make decisions.

Requirements
Python 3.x
NumPy package (pip install numpy)
How to Play
To start the game, run python tictactoe.py in the terminal. You will be prompted to choose the game mode:

Player vs. Player (type 1)
Player vs. AI (type 2)
AI vs. AI (type 3)
If you choose to play against the AI, you will be prompted to choose your symbol (X or O). The AI will take the other symbol.

During the game, the board will be displayed on the console. To make a move, type in the row and column number where you want to place your symbol (e.g. 1,1 for the top-left corner).

How it Works
The AI opponent uses the Minimax algorithm to determine the best move to make. The algorithm works by recursively evaluating all possible moves and choosing the one that maximizes the AI's chance of winning or minimizes its chance of losing. This means that the AI is always playing optimally and can never be beaten if played perfectly.

To speed up the decision-making process, the algorithm also implements alpha-beta pruning, which helps to reduce the number of nodes that need to be evaluated.

Credits
This project was inspired by this tutorial by Tech With Tim. The Minimax algorithm implementation is based on the Wikipedia article.

License
This project is licensed under the MIT License. Feel free to use it for any purpose.
