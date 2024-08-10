# Tic-Tac-Toe

Global Variables

Board: A 3x3 array to represent the game grid. Initially filled with numbers 1 to 9 indicating slot positions.
Current Marker: A character ('X' or 'O') representing the marker of the current player.
Current Player: An integer (1 or 2) indicating which player's turn it is.
Main Steps of the Program


Initialization:

Initialize the board with numbers 1 to 9.
Prompt Player 1 to choose their marker ('X' or 'O').
Set the initial player to Player 1 and the marker to the chosen one.

Draw Board:

Display the current state of the board to the console with markers ('X' or 'O') in the occupied slots and numbers in the empty slots.

Place Marker:

Convert the chosen slot number to the corresponding row and column in the 3x3 grid.
Check if the slot is available (not already occupied by 'X' or 'O').
If available, place the current marker in the chosen slot. Otherwise, prompt for another input.

Check for Winner:

Check all rows, columns, and diagonals for three matching markers ('X' or 'O').
If any row, column, or diagonal has three matching markers, declare the current player as the winner.
If no winner is found and all slots are filled, declare a tie.

Swap Player and Marker:

Switch the current marker from 'X' to 'O' or 'O' to 'X'.
Switch the current player from Player 1 to Player 2 or Player 2 to Player 1.

Game Loop:

Repeat the following steps for a maximum of 9 turns (one for each slot):
Draw the current state of the board.
Prompt the current player to choose a slot.
Validate the slot choice and place the marker if valid.
Check for a winner after placing the marker.
If a winner is found, announce the winner and end the game.
If no winner is found, swap the player and marker for the next turn.
If all slots are filled without a winner, declare a tie.

Detailed Workflow

Start Game:

Initialize the board and prompt Player 1 to choose their marker.
Set the current player to Player 1 and the current marker to the chosen marker.

Game Loop:

For each turn (up to 9 turns):
Display the current state of the board.
Prompt the current player to enter a slot number.
Validate the input:
If the input is invalid (not in the range 1-9 or slot already occupied), prompt again.
If valid, place the marker in the chosen slot.
After placing the marker, check for a winner:
Check all rows, columns, and diagonals for three matching markers.
If a winner is found, announce the current player as the winner and end the game.
If no winner and slots are still available, swap the player and marker for the next turn.
If all slots are filled without a winner, declare the game a tie.

End Game:


Announce the winner if there is one.
If no winner and all slots are filled, declare the game a tie.
