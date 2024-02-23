# Game-with-Q-learning-AI

This project implements the game of Nim along with an AI player that learns to play the game using Q-learning.

## Nim Game

Nim is a mathematical game of strategy where two players take turns removing objects from distinct heaps or piles. In this implementation, the game starts with several piles, each containing a certain number of objects. Players take turns removing any number of objects from a single pile. The player who removes the last object(s) wins.

## How to Play

To play the game against the AI, follow these steps:

1. Run the `play()` function with the AI as an argument.
2. The game will start, and you will be prompted to choose a pile and the number of objects to remove. Enter your choices when prompted.
3. The AI will then make its move.
4. Continue taking turns until one player wins.

## Training the AI

You can train the AI by having it play against itself. Use the `train(n)` function to train the AI by playing `n` games against itself.

## Files

- `nim.py`: Contains the implementation of the Nim game and the Q-learning AI.
- `README.md`: This file, providing information about the project.

## Requirements

- Python 3.x

## Usage

To play the game against the AI:

```bash
python nim.py
