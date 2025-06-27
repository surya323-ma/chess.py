# chess.py
♟️ Interactive Chess Game in Google Colab
This project implements a basic interactive Chess game using Python and IPyWidgets, fully playable within a Google Colab notebook. You can play either against another human player or a simple AI-controlled computer opponent.

📌 Features
Interactive chessboard rendered with ipywidgets

Supports two game modes:

Two Players (hot-seat mode)

Vs Computer (random move AI)

Visual highlighting of:

Selected pieces (green)

Valid move targets (red)

Basic move rules for all standard chess pieces

Automatic pawn promotion to queen

Simple win condition (king capture)

📂 Requirements
To run the game, your environment must support:

Python 3

IPython display (IPython.display)

NumPy

ipywidgets (automatically supported in Google Colab)

✅ Recommended: Use Google Colab for best compatibility.

🚀 How to Run
Open this project in Google Colab.

Run all cells to launch the game.

The interactive chessboard will appear. Select a game mode and start playing!

🎮 Controls
Click a piece to select it.

Click a red-highlighted square to move the selected piece.

Click the same piece again to deselect.

Use the reset button to restart the game.

Switch between "Two Players" and "Vs Computer" anytime.

🤖 Computer AI
The computer makes random valid moves when in "Vs Computer" mode. It does not employ any strategy or lookahead.
