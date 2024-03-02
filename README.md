Tic Tac Toe Web Game

This repository contains a simple Tic Tac Toe game implemented using HTML, CSS, and JavaScript. Players can take turns clicking on cells to mark them as 'X' or 'O' and the game will automatically determine the winner or declare a draw.

 Features:

- **Game Board**: A 3x3 grid where players can click on cells to place their marks.
- **Win Detection**: The game automatically detects when a player has won by getting three marks in a row (horizontally, vertically, or diagonally).
- **Draw Detection**: If all cells are filled without a winner, the game declares a draw.
- **Reset Functionality**: Players can reset the game board at any time to start a new game.

 Usage:
 
1. Open HTML File: Open the 'index.html' file in any web browser to start playing the game.

2. Gameplay:
   - Click on any cell in the grid to place your mark ('X' or 'O').
   - The game will automatically switch turns between players ('X' and 'O').
   - The game will declare the winner when a player achieves three marks in a row or declare a draw if no winner is found.

 Files Included:

- index.html: Contains the HTML structure and elements for the Tic Tac Toe game.
- styles.css: Defines styles for the HTML elements to improve visual presentation.
- script.js: Implements JavaScript functionality for the game, including game logic and event handling.

 Notes:

- The game board is represented as an array of strings, where each string represents the mark ('X', 'O', or empty) in each cell.
- Win conditions are checked using an array of arrays representing winning combinations.
- The game board is reset by clearing the array and resetting the current player to 'X'.

Enjoy playing Tic Tac Toe!
