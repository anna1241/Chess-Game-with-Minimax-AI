# Chess Game with Minimax AI

## Overview

This project is a Chess Game implemented with an AI opponent that uses the Minimax algorithm. The AI is designed to play against a human opponent and make strategic decisions to maximize its chances of winning.

## Features

- **Human vs AI**: Play against an AI opponent that uses the Minimax algorithm.
- **User-Friendly Interface**: Interactive graphical user interface for easy gameplay.
- **Move Validation**: Ensures all moves made by both the human and AI are valid according to chess rules.
- **Minimax Algorithm**: AI uses the Minimax algorithm with alpha-beta pruning to evaluate and choose the best moves.
- **Difficulty Levels**: Adjustable depth of the Minimax algorithm to set different difficulty levels for the AI.

## How It Works

1. **Game Initialization**: The game initializes the chessboard and sets up pieces for both players.
2. **Player Move**: The human player makes a move by interacting with the graphical interface.
3. **AI Move**: The AI calculates the best move using the Minimax algorithm with alpha-beta pruning and makes its move.
4. **Game Loop**: The game alternates between the human player and AI until a checkmate, stalemate, or draw is reached.
