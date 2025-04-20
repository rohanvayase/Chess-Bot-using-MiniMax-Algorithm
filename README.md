# ♟️ AI Chess Game with Minimax Algorithm
This is a browser-based Chess AI project developed using JavaScript and the p5.js library. The application pits a human player against a basic AI opponent powered by the Minimax algorithm with Alpha-Beta pruning.

🎯 Features
Full 8x8 chessboard with all standard chess pieces.

AI logic implemented via the Minimax algorithm and Alpha-Beta pruning for optimized decision-making.

Adjustable AI search depth to control difficulty.

Human vs. AI gameplay experience.

Graphical interface using p5.js with interactive piece movement.

🧠 How the AI Works
The AI calculates possible board states using:

minFun and maxFun for standard minimax.

minFunAB and maxFunAB for improved performance with Alpha-Beta pruning.

The board is evaluated based on piece values, and it aims to maximize (or minimize) score depending on the player's side.

🗂️ Project Structure
pgsql
Copy
Edit
/index.html              - Entry point, sets up the canvas and scripts

/sketch.js               - p5.js core setup, draw loop, and game state handling

/Board.js                - Board state, piece management, and game logic

/Piece.js                - Definitions for all chess pieces and their movement rules

/MinimaxFunctions.js     - Minimax algorithm and Alpha-Beta pruning logic

/assets/                 - Images for chess pieces (make sure this is present)

🚀 Getting Started
Clone or download this repository.

Make sure the assets folder contains chess piece sprites (2000px-Chess_Pieces_Sprite_01.png to 2000px-Chess_Pieces_Sprite_12.png).

Open index.html in any modern browser.

You should see a chessboard and can start playing against the AI right away!

⚙️ Controls
Click to select and move pieces.

Use the + and - buttons on the screen to adjust the AI's thinking depth (how many moves ahead it considers).

AI automatically plays as Black by default, but you can tweak it in sketch.js.

📷 Preview
(Add a screenshot or GIF here if desired)

📌 To Do / Future Enhancements
Add full support for special moves like castling, en passant, and promotion.

Implement move history and undo feature.

Enhance the evaluation function for smarter AI behavior.

Add sound effects and better UI feedback.

🧑‍💻 Author
Created as part of an Artificial Intelligence project.

