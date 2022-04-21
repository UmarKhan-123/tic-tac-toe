# tic-tac-toe AI Game

Tic-Tac-Toe is normally played with two people. One player is <b>X</b> and the other player is <b>O</b>. Players take turns placing their <b>X</b> or <b>O</b>. If a player gets three of their marks on the board in a row, column, or diagonal, they win. When the game board fills up with neither player winning, the game ends in a draw.

The Algorithm for the game is:

1. See if there’s a move the computer can make that will win the game. If there is, take that move. Otherwise, go to step 2.

2. See if there’s a move the player can make that will cause the computer to lose the game. If there is, the computer should move there to block the player. Otherwise, go to step 3.

3. Check if any of the corners (spaces 1, 3, 7, or 9) are free. If no corner space is free, go to step 4.

4. Check if the center is free. If so, move there. If it isn’t, go to step 5.

5. Move on any of the sides (spaces 2, 4, 6, or 8). There are no more steps, because the side spaces are the only spaces left if the execution has reached this step.
