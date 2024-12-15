# CliffBoxPushing Grid Game Using Reinforcement Learning

This project implements a CliffBoxPushing grid game using various reinforcement learning algorithms. The focus is on exploring Q-learning, SARSA, and UCB (Upper Confidence Bound) methods to solve sequential decision-making problems in a Markov Decision Process (MDP).

## Features

- **Q-Learning**: Implements the off-policy Q-Learning algorithm for optimizing actions in an MDP.
- **SARSA**: Explores the on-policy SARSA algorithm for learning state-action value functions.
- **UCB**: Utilizes the Upper Confidence Bound algorithm for addressing exploration-exploitation trade-offs.
- **Visualization**: Generates value and policy tables to understand the agent's decision-making process.

## Prerequisites

- Python 3.8 or higher
- Libraries: `numpy`, `matplotlib`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ThanyaRamanathan/CliffBoxPushing-Game.git

2. Install requirements:
   ```bash
   pip install -r requirements.txt

## Outputs
- Value Tables: Show estimated cumulative rewards for states.
- Policy Tables: Represent the optimal policy derived from the algorithms.
- Performance Metrics: Track convergence and learning efficiency.

## Inferences
- Q-Learning vs. SARSA:
  - Q-Learning learns faster due to its off-policy nature, achieving positive rewards within 10,000 episodes.
  - SARSA, being on-policy, takes a more cautious approach, requiring 25,000 episodes for similar performance.
- UCB Advantages:
  - Balances exploration and exploitation dynamically.
  - Provides faster convergence in uncertain environments compared to ε-greedy strategies.

## Improvements
- Implement Deep Q-Networks (DQNs) for high-dimensional state spaces.
- Explore hybrid approaches combining Q-Learning and UCB.
- Integrate adaptive exploration strategies.
