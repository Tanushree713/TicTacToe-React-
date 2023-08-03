# TicTacToe Game
This is a simple TicTacToe game built using React and Grid.js library. It allows two players to play the game on a 3x3 grid.

# How to Play
Clone the repository to your local machine.
Make sure you have Node.js and npm installed.
Open a terminal and navigate to the project's root directory.
Run npm install to install the required dependencies.
Run npm start to start the development server.
Open your web browser and go to http://localhost:3000 to play the game.
# How to Play
The game starts with an empty 3x3 grid.
Player 1 is assigned the symbol "O", and Player 2 is assigned the symbol "X".
Players take turns to click on any unoccupied cell in the grid to make their move.
The game will automatically detect a win or a draw and display the result.
If a player wins, the winning line will be highlighted, and the winner's symbol will be displayed.
To start a new game after a win or draw, click the "Reset Game" button.
# Components
Grid.js: This component manages the game state, including the board, the current turn, and the winner. It renders the game grid and individual cards using the Card component. It uses the isWinner function from winner.js to determine the winner.

Card.js: This component represents a single cell in the grid. It displays the symbol of the player who made the move and is responsible for calling the play function in the Grid component when clicked.

winner.js: This module contains the isWinner function, which checks if a player has won the game based on the current board state.

Icon.js: This component renders the icons for each player's symbol (circle, cross, or pen).

# Contributing
If you find any issues with the game or have suggestions for improvement, feel free to create a new issue or submit a pull request. We welcome contributions from the community!

# License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as you like.

# Acknowledgments
The TicTacToe game logic is inspired by various tutorials and resources available online.
The Grid.js library used in this project provides a simple way to manage game state using React hooks.
