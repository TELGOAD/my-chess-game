JavaScript Chess Game by Aditya
Welcome to the JavaScript Chess Game project—a browser-based chess game built using HTML, CSS, and JavaScript. This project provides a simple yet interactive chess-playing experience, complete with move highlighting, piece capture, and special moves like castling.

Table of Contents
Overview
Features
Installation & Usage
Project Structure
How to Play
Dependencies
Credits
License
Overview
This project is a fully-functional chess game implemented in JavaScript. It uses HTML to define the board layout, CSS for styling and animations, and JavaScript to handle game logic and user interactions. The game initializes a standard chess board, places all pieces in their starting positions, and allows two players to take turns moving their pieces.

Features
Interactive Chess Board: The board is rendered using HTML elements and styled with CSS.
Chess Piece Movement: Supports standard chess moves including capturing opposing pieces.
Special Moves: Features like castling are implemented.
Move Highlighting: When a piece is selected, all possible moves are highlighted for the player's convenience.
Turn-based Play: A turn indicator shows whether it's White's or Black's turn.
Animations: CSS animations enhance user experience with visual effects during moves and highlights.
Installation & Usage
Clone the Repository:

bash
Copy
Edit
https://github.com/TELGOAD/my-chess-game.gitcd chess-game

Open the Game:

Simply open the index.html file in your preferred web browser.

bash
Copy
Edit
open index.html
Alternatively, you can host the files on a local server if needed.

Start Playing:

The chess board will load with pieces in their standard positions. Click on a piece to see its possible moves and click on a highlighted cell to move.

Project Structure
index.html:
Contains the HTML structure for the chess board and the layout of the game. It links to the CSS and JavaScript files.

style.css:
Provides styling for the chess board, cells, and animations. It includes classes for highlighting moves and various neon effects.

script.js:
Contains the core game logic including piece movement, move option calculations, turn management, and event handlers for user interactions.

How to Play
Select a Piece:
Click on a chess piece. Only pieces belonging to the current turn will show their move options.

View Move Options:
Once selected, the game highlights all valid moves (cells) for that piece.

Make a Move:
Click on one of the highlighted cells to move the piece. If the cell contains an opponent's piece, it will be captured.

Special Moves:

Castling: When conditions are met (e.g., neither the king nor the involved rook has moved), castling can be executed by selecting the king and choosing the appropriate highlighted cell.
Pawn Movement: Supports first-move two-cell advances and capturing diagonally.
Turn Indicator:
The turn indicator updates after every move, alternating between "It's Whites Turn!" and "It's Blacks Turn!".

Dependencies
jQuery:
The game utilizes jQuery (loaded from a CDN) for DOM manipulation and event handling.
