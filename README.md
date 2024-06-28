# Tic-Tac-Toe AI using Minimax Algorithm with Alpha-Beta Pruning

This project implements an AI player for Tic-Tac-Toe using the Minimax algorithm with Alpha-Beta pruning. It includes different aspects such as the basic implementation of the game, optimization with Alpha-Beta pruning, parallelization for performance improvement, and an enhanced version using heuristics.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Setup](#setup)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
4. [Usage](#usage)
5. [Algorithm Details](#algorithm-details)
    - [Minimax Algorithm](#minimax-algorithm)
    - [Alpha-Beta Pruning](#alpha-beta-pruning)
    - [Parallelization](#parallelization)
    - [Heuristic Evaluation](#heuristic-evaluation)
6. [Performance Comparison](#performance-comparison)
7. [Future Enhancements](#future-enhancements)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

This project implements a Tic-Tac-Toe game AI using Python, focusing on the Minimax algorithm with Alpha-Beta pruning. The AI is designed to play optimally against a human player, making decisions based on the game state evaluation without exploring unnecessary branches of the game tree.

## Features

- **Basic Tic-Tac-Toe Game**: Implements a simple console-based Tic-Tac-Toe game where a human player can play against the AI.
  
- **Minimax Algorithm**: Utilizes the Minimax algorithm to evaluate the game state and choose the best possible move for the AI.
  
- **Alpha-Beta Pruning**: Optimizes the Minimax algorithm by implementing Alpha-Beta pruning, reducing the number of nodes evaluated and improving performance.
  
- **Parallelization**: Offers a parallelized version of the Alpha-Beta pruning algorithm using multithreading to further enhance performance on multicore systems.
  
- **Heuristic Evaluation**: Includes an enhanced version of the AI using heuristic evaluation for non-terminal game states, allowing quicker pruning of unpromising branches.

## Setup

### Prerequisites

To run this project, ensure you have the following installed:

- Python 3.x
- [ThreadPoolExecutor](https://docs.python.org/3/library/concurrent.futures.html#threadpoolexecutor) (for parallelization, included in Python standard library)

### Installation

Clone the repository:

```bash
git clone https://github.com/your-username/tic-tac-toe-minimax.git
cd tic-tac-toe-minimax
```

No additional packages are required beyond Python's standard library.

## Usage

To play the Tic-Tac-Toe game against the AI, simply run:

```bash
python main.py
```

Follow the on-screen instructions to make your moves against the AI. The AI will respond with its optimal moves based on the Minimax algorithm with Alpha-Beta pruning.

## Algorithm Details

### Minimax Algorithm

The Minimax algorithm is a decision-making algorithm that is used for finding the optimal move in a two-player, zero-sum game.

### Alpha-Beta Pruning

Alpha-Beta pruning is an optimization technique for the Minimax algorithm that reduces the number of nodes evaluated in the search tree.

### Parallelization

Parallelization using Python's `ThreadPoolExecutor` allows the Alpha-Beta pruning algorithm to evaluate multiple potential moves concurrently, improving performance on multicore processors.

### Heuristic Evaluation

Heuristic evaluation is used to estimate the desirability of a game state without exploring all possible moves. It guides the AI to prioritize more promising branches of the game tree, thereby reducing search space.

## Performance Comparison

The performance of the AI with and without Alpha-Beta pruning, as well as the parallelized version, can be compared in terms of the number of nodes evaluated and execution time.

## Future Enhancements

- **Graphical User Interface (GUI)**: Implement a GUI for a more interactive gameplay experience.
  
- **Deep Learning Integration**: Explore using deep learning models to enhance AI decision-making in complex game scenarios.
  
- **Extended Game Support**: Extend the AI to support other board games with similar two-player, zero-sum characteristics.

## Contributing

Contributions are welcome! Fork the repository and submit pull requests for any enhancements or bug fixes. Please open an issue to discuss major changes beforehand.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

