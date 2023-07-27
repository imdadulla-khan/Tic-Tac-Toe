# Tic-Tac-Toe Game

This is a simple implementation of a Tic-Tac-Toe game in Python. The game allows two players to take turns and try to get three of their symbols in a row on the 3x3 game board.

## How to Play

1. Clone or download the code from this GitHub repository.

2. Run the Python script in your terminal or IDE.

3. Two players will be created, "Player 1" with the symbol "X" and "Player 2" with the symbol "O".

4. The game will ask each player to make their moves alternately by specifying the position they want to place their symbol (X or O) on the board.

5. The positions are numbered from 0 to 8, starting from the top-left corner of the board and going right and down in row-major order.

6. The game will check for a win condition after each move and display the winner or declare it a draw if the board is full and no player has won.

## Classes and Functions

1. **`greeting` Class**: A class that contains a method to greet the current player before their turn.

2. **`Player` Class**: A base class for both human players (`Player1` and `Player2`) and a `ComputerPlayer` class that can be implemented in the future.

3. **`Player1` Class**: Inherits from `Player` and represents "Player 1" with the symbol "X". It has a method `__move()` that is invoked when the player wins.

4. **`Player2` Class**: Inherits from `Player` and represents "Player 2" with the symbol "O". It also has a method `__move()` that is invoked when the player wins.

5. **`checkings` Class**: A class that checks for a win condition on the game board.

6. **`playGame` Class**: Inherits from `checkings`, `greeting`, `Player1`, and `Player2`. It manages the game flow, taking player moves and checking for wins or draws.

7. **`Board` Class**: Represents the game board with a list of tiles. It can arrange and print the current board state.

8. **`Move` Class**: Represents a move by a player and asks for input from the user.

## How to Run

1. Open a terminal or command prompt.

2. Navigate to the directory where the Tic-Tac-Toe Python script is located.

3. Run the following command to execute the game:

```
python <filename>.py
```

4. Follow the on-screen instructions to play the game. Enter the number of the position you want to place your symbol.

5. The game will continue until there is a winner or the board is full, resulting in a draw.

Enjoy playing Tic-Tac-Toe!
