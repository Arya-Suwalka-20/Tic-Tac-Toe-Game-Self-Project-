# Tic Tac Toe AI Bot

## Introduction

This repository contains an implementation of a Tic Tac Toe AI bot designed to play optimally against any opponent. It demonstrates concepts from Artificial Intelligence and Game Theory, allowing you to explore these exciting fields.

## Project Structure

* `q1.py`: The core file containing the Tic Tac Toe AI logic.
* `AI.pdf`: Study material on Artificial Intelligence concepts. (Optional: Consider including links to online resources instead of PDFs)
* `Tictactoe_Ques.pdf`: Project questions and prompts. (Optional: Consider including links to online resources instead of PDFs)
* `README.md`: This file (you're reading it now!).

## Understanding the Code (q1.py)

The `q1.py` file implements the AI logic using techniques like:

* Minimax Algorithm (or an alternative AI approach)
* Alpha-Beta pruning (if applicable)

**Explanation of Key Functions:**

* `is_win(self)`: Determines if a given player has won the game.
* `is_draw(self)`: Checks if the game is a draw.
* `get_valid_actions(self)`: Returns available moves for the current player.
* `is_terminal_history(self)`: Indicates if a game state is considered terminal (win, draw, or full board).
* `get_utility_given_terminal_history(self)`: Assigns a utility score based on the game outcome (e.g., +1 for win, 0 for draw, -1 for loss).
* `update_history(self, action)`: Updates the game history with the chosen action.
* `backward_induction(history_obj)`: (Optional) Implements a dynamic programming approach like backward induction (if used).

## Customization

You can modify the provided AI approach (e.g., experiment with different algorithms) or explore advanced optimizations. Consider visualizing the game state for better understanding and user interaction.

## License

This project uses the MIT License. Feel free to use and modify the code according to the terms.

## Contribution

Pull requests and suggestions are welcome! Create a pull request to share your improvements.

## Further Learning

The provided PDFs (or online resources) offer foundational knowledge on AI and Game Theory. Explore online tutorials and libraries like Minimax and Alpha-Beta pruning for more in-depth analysis.