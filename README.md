# Nim AI with Reinforcement Learning
<img src="https://i.imgur.com/IqOLsqK.jpg">

## Overview
This project implements an artificial intelligence (AI) that learns to play the game of Nim through reinforcement learning, specifically using Q-learning. Nim is a mathematical game of strategy where players take turns removing objects from heaps or piles. In this project, the AI plays against itself repeatedly, learning from its experiences to improve its strategy over time.

```powershell
$ python play.py
Playing training game 1
Playing training game 2
Playing training game 3
...
Playing training game 9999
Playing training game 10000
Done training

Piles:
Pile 0: 1
Pile 1: 3
Pile 2: 5
Pile 3: 7

AI's Turn
AI chose to take 1 from pile 2.
```

## Key Features
- **Reinforcement Learning**: Utilizes Q-learning, a model-free reinforcement learning algorithm, to determine the optimal strategy.
- **Self-Learning**: The AI trains by playing against itself, learning which actions are best in different game states.
- **Python Implementation**: Implemented in Python, showcasing proficiency in a key data science programming language.

## Technologies Used
- Python 3.10
- Libraries: Standard Python libraries

## AI Strategy
The AI's decision-making process is based on evaluating the current state of the game and selecting actions (removing objects from piles) that maximize its chance of winning, according to learned Q-values.

## Project Structure
- `nim.py`: Contains the implementation of the Nim game and the AI player.
- `play.py`: Script to play the game against the trained AI.
- `README.md`: Documentation for the project.

## Key Concepts Demonstrated
- **Q-Learning**: Implementing the Q-learning algorithm to learn game strategy.
- **Game Theory**: Application of game theory in AI.
- **Python Programming**: Advanced Python concepts, including classes and dictionary manipulations.

## Setup and Usage
1. Clone the repository.
2. Run `python play.py` to start playing against the AI.

## Development Process
- **Implementation of Q-Learning Functions**: Developed functions to calculate Q-values, update them, and choose actions based on these values.
- **Training the AI**: The AI was trained by simulating thousands of games against itself.
- **Optimization and Testing**: Continuous testing and optimization to improve AI performance.

## Challenges and Learning
- Implementing and fine-tuning the Q-learning algorithm for a specific game scenario.
- Understanding the balance between exploration (trying new actions) and exploitation (using known successful actions).
