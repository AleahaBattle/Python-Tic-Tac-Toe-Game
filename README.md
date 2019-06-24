# Python Tic-Tac-Toe Game

<p align="center">
	<img src="board_image.png"></img>
</p>

System Requirements: Python 3

| Filename        | Description                                                                                |
|-----------------|--------------------------------------------------------------------------------------------|
| tictactoe.py    | user vs computer game                                                                      |


## How does it work?
A Tic-Tac-Toe computer program that can intelligently respond to the player’s moves. Tic-Tac-Toe is normally played with two people. One player is X and the other player is O. Players take turns placing their X or O. If a player gets three of their marks on the board in a row, column, or diagonal, they win. When the board fills up with neither player winning, the game ends in a draw.


## Understanding the Program
The computer searches for the best move that leads the player to lose (or tie). It consider the current state of the game and the available moves at that state, then for each valid move it plays, until it finds a terminal state (win, draw or lose).
