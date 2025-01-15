<h1> Tic_Tac_Toe_vs_AI </h1>

# Overview
*This project is a simple console-based Tic-Tac-Toe game implemented in Python. The game allows a human player to compete against an AI player. The player takes the symbol 'X' while the AI plays as 'O'.
The AI has basic logic to block the player's winning moves and make its own winning moves where possible. The game alternates turns until a winner is determined or the board is full (resulting in a draw).*

# Features
*1.Interactive Gameplay:
    Players can input positions (1-9) to make their moves.
    The board updates dynamically after every turn.
2.AI Opponent:
    The AI evaluates the board to make strategic moves.
    Blocks player's winning moves and attempts to secure its own wins.
3.Win Detection:
    Horizontal, vertical, and diagonal win conditions are checked for both the player and the AI.
4.Draw Detection:
    The game announces a draw if all spaces are filled without a winner.*

# How to Run
*1.Ensure you have Python installed (Python 3.x is recommended).
2.Copy the script into a Python file (e.g., tic_tac_toe.py).
3.Open a terminal or command prompt and navigate to the folder containing the script.
4.Run the script using the command:
    python tic_tac_toe.py*
    
# How to Play
*1.The game displays a 3x3 grid with positions numbered 1 to 9.
2.Players take turns entering their moves by selecting a number corresponding to an empty position on the grid.
3.The board updates, and the AI makes its move automatically after the player.
4.The game ends when:
    The player or AI aligns three of their symbols ('X' or 'O') in a row, column, or diagonal.
    The board is full, resulting in a draw.*

# File Structure
*1.printBoard(board):-             Displays the current state of the board.
2.IsWinner(board, letter):-        Checks if the given letter ('X' or 'O') has won the game.
3.spaceIsFree(pos):-               Checks if a specific position on the board is empty.
4.insertLetter(letter, pos):-      Inserts a letter ('X' or 'O') at a specified position.
5.playerMove(symbol):-             Allows the player to make their move by inputting a position.
6.Play(AIPlayer):-                 Runs the main game loop, alternating between the player and AI turns.
7.AIPlayer(board):-                Determines the AI’s next move using simple heuristics to block the player's                                           winning moves or make its own winning moves. If no strategic move is available, 
                                   it selects a random empty position.*

# Dependencies (Only Python Standard Library)
    *The game uses only standard Python libraries, so no additional dependencies are required.*

# Potential Improvements
*1.Enhanced AI:
    Implement a minimax algorithm for unbeatable AI.
2.GUI:
    Develop a graphical user interface for better user interaction.
3.Multiplayer Mode:
    Allow two players to compete without an AI.
4.Additional Features:
    Add score tracking across multiple rounds.
    Include difficulty levels for the AI.*

# License
    *This project is open-source and can be freely modified and distributed.*
# Acknowledgement
    *This project was developed as a practice exercise to demonstrate basic game logic and AI implementation in            Python.*


    

