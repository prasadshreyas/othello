# Othello (Reversi) Game Implementation

## Overview

This repository contains a Python implementation of the classic board game Othello, also known as Reversi. The game is played on an 8x8 grid, and the objective is to have the most pieces of your color (either white or black) on the board when the game ends.

## Features

- Supports interactive gameplay for two players: one player as white and the other as black.
- Implements a simple AI player for white that uses the minimax algorithm with alpha-beta pruning to make strategic decisions.
- Includes a basic text-based user interface for playing the game.

## Getting Started

To play the game, simply run the script in your Python environment. Follow the on-screen instructions to make your moves.

## Game Rules

The game follows the standard rules of Othello. Some key rules include:
- Players take turns placing their pieces on the board.
- To make a valid move, you must place a piece in such a way that it surrounds your opponent's pieces in a straight line. This causes all of the opponent's pieces in that line to flip to your color.
- The game ends when no more valid moves can be made.
- The player with the most pieces of their color on the board wins.

## AI Player

The AI player (white) uses the minimax algorithm with alpha-beta pruning to make strategic decisions. You can adjust the search depth in the code to control the AI's level of difficulty.
