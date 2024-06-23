#Chess Game

Welcome to the Chess Game project! This project is a fully-featured chess game developed in [Your Preferred Language/Framework]. It supports human vs. human gameplay, including all standard chess rules and features.

##Features

Human vs. Human: Play chess locally with another person.
Standard Chess Rules: All rules of chess are implemented, including castling, en passant, and pawn promotion.
Interactive GUI: A user-friendly graphical interface for easy gameplay.
Move History: Track all moves made in the game.

##Game Rules
###Basic Rules
1. Objective: The primary goal of chess is to checkmate your opponent's king. This occurs when the king is in a position to be captured ("in check") and there is no legal move to escape the check.
2. Movement:
- King: Moves one square in any direction.
- Queen: Moves any number of squares along a row, column, or diagonal.
- Rook: Moves any number of squares along a row or column.
- Bishop: Moves any number of squares diagonally.
- Knight: Moves in an L-shape: two squares in one direction and then one square perpendicular.
- Pawn: Moves forward one square but captures diagonally. On its first move, a pawn can move forward two squares.
###Special Rules
3. Pawn Promotion: When a pawn reaches the opposite end of the board, it must be promoted to a queen, rook, bishop, or knight of the same color.
4. Castling: A move that involves the king and either rook. The king moves two squares towards the rook, and the rook moves to the square next to the king. Castling has several conditions:
- Neither the king nor the rook involved has previously moved.
- No pieces are between the king and the rook.
- The king is not currently in check, and the squares the king passes through are not under attack.
5. En Passant: A special pawn capture that can occur immediately after a pawn makes a move of two squares from its starting position. The opposing pawn can capture the moving pawn as if it had moved only one square.
6. Check: A king is in check if it is under attack by an opponent's piece. A player must make a move that removes the check.
7. Checkmate: A checkmate occurs when a king is in check and there is no legal move to escape the check, resulting in a win for the attacking player.
8. Stalemate: A stalemate occurs when a player has no legal move and their king is not in check. This results in a draw.


<img width="800" alt="Before Castling" src="https://github.com/rippondoragithub/rippondoragithub/assets/173114135/a2ee2173-0d69-4e4c-b247-d5376056ede9">

<img width="799" alt="After Castling" src="https://github.com/rippondoragithub/rippondoragithub/assets/173114135/a3aa8cdd-3f73-4b69-800e-4089e9ff797b">


##How It Works

###Architecture
- Board Representation: The board is represented using a 2D array to manage the positions of the pieces.
- Game Logic: The game logic, including move validation, check/checkmate detection, and special rules.
- User Interface: The graphical user interface (GUI) is built using pygame.
###Highlights
- Robust Move Validation: Ensures all moves comply with chess rules, including special moves like castling and en passant.
- Real-Time Move Updates: The board updates in real-time to reflect the current game state.
- Move History Tracking: Keeps a record of all moves made during the game for review and analysis.

##Usage
- Upload 'Chess Game.ipynb' into Jupyter Notebook
- Upload piece images into Jupyter Notebook and make sure they are named correctly. See the code for PIECES in 'Chess Game.ipynb' to see the pieces are named.
- Run the Game

##Conclusion

This chess game project demonstrates a comprehensive implementation of a classic chess game with a focus on human vs. human gameplay. The project covers all standard chess rules and provides a robust, interactive experience for players.

Feel free to explore the game, enjoy playing, and dive into the code to see how the chess logic is implemented!
