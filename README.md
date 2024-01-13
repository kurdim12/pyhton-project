# pyhton-project 
tic-tac-toe game.

Description:
This Python script implements a simple command-line Tic-Tac-Toe game. The game allows for two modes of play: single-player against a computer opponent or two-player mode. The players take turns making moves on a 3x3 game board, and the game continues until a player wins, the board is full (resulting in a draw), or the players choose to end the game.

Functions:

greet_player(): Displays a welcome message with ASCII art.

print_board(board): Displays the current state of the Tic-Tac-Toe board.

check_winner(board, player_symbol): Checks if the specified player has won the game.

is_board_full(board): Checks if the game board is full.

prompt_for_move(player, sign, board): Prompts the player for a move and validates it.

check_if_valid_move(move_location_value): Checks if the chosen cell is empty.

get_computer_move(board): Generates a random move for the computer player.

make_move(board, player_symbol, row, column): Updates the game board with the player's move.

switch_player(current_player_symbol): Switches the current player symbol between "X" and "O".

two_player_add_info(): Gets player names for two-player mode.

single_player_add_info(): Gets the player name and chooses player order for single-player mode.

two_player_round(): Executes a round of the game for two players.

single_player_round(): Executes a round of the game for a single player against the computer.

choose_playstyle(): Allows the user to choose the playstyle (single-player or two-player).

sort_leaderboard(leaderboard): Sorts the leaderboard in descending order by scores.

print_leaderboard(leaderboard): Prints the leaderboard.

play_another_game(): Asks if the player wants to play another game.

main(): The main function to run the game. It initializes the game, processes player moves, updates the leaderboard, and allows the player to play another game.

Usage:
To play the game, run the script in a Python environment. Follow the prompts to choose the playstyle, enter player names, and make moves during the game. The leaderboard keeps track of the scores, and the game can be replayed multiple times.
