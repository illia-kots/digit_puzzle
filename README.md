# Digit Puzzle Game

Implement the Digit Puzzle Game like in this [LAYOUT LINK](https://play2048.co/)

**Project task:**
 1. The game field is 4 x 4
 1. Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
 1. The player can move cells with keyboard arrows
 1. All the numbers should be moved in the selected direction until all empty cells are filled in
     - 2 equal cells should be merged into a doubled number
     - The merged cell can’t be merged twice during one move
 1. The move is possible if at least one cell is changed after the move
 1. After move 2 or 4 appears in a random empty cell. 4 probability is 10%
 1. When 2048 value is displayed in any cell, win message should be shown.
 1. The game over message should be shown if there are no more available moves.
 1. Hide start message when game starts.
 1. Change the Start button to Restart after the first move.
 1. Increase score with each move. The score should be increased by the sum of all merged cells.

**Tech stack:**
  - HTML
  - CSS/SCSS
  - JavaScript


[PREVIEW LINK](https://illia-kots.github.io/digit_puzzle_game/)
