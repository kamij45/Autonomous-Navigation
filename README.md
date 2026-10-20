# Autonomous-Navigation
A tabular Q-learning agent that learns to navigate the FrozenLake Enviroment, a grid world from the gymnasium library. 
The trained agent is compared against a random baseline to show how much the agent learns.

## Overview
Autonomous navigation boils down to how an agent learns to reach a goal without being told the route. This project answers it with the simplest reinforcement learning method, **Q-learning**, in a small environment where every part of the process is easy to inspect.

## Hyperparameters 
1. alpha - 0.1
2. gamma - 0.99
3. epsilon - 1.0
4. epsilon_min - 0.05
5. epsilon_decay - 0.999
6. episodes - 10000
7. max_steps - 100

## Results
Both agents were evaluated over 1000 episodes,  using the the epsilon greedy strategy   for the Q-learning agent. The Q-learning reaches the goal in every episode , since the environment is_slippery= False, its **Deterministic** or **Predictable**
**Q-learning Agent**
Success Rate = 100%
Average Reward = 1.000
**Random Agent**
Success Rate = 1.40%
Average Reward = 0.014

## Tools
1. Python
2. Gynmasium
3. Matplotlib
4. Numpy

## Author
Onodingene Kamsiyochukwu
