# SE4050 - Deep Learning Lab 08

## Reinforcement Learning

This repository contains the completed work for SE4050 Deep Learning Lab 08.

### Student Details

- Registration Number: IT23177482
- Module: SE4050 - Deep Learning
- Lab: 08
- Topic: Reinforcement Learning

## Lab Objectives

The main objective of this lab is to understand and implement different reinforcement learning approaches, including:

- Markov Decision Process
- Policy Evaluation
- Value Iteration
- Policy Iteration
- Q-Learning
- Model-Based vs Model-Free Reinforcement Learning
- Deep Q-Learning (DQN)
- Epsilon-Greedy Action Selection

## Question 1 - Markov Decision Process and Q-Learning

The following tasks were completed:

- Implemented iterative policy evaluation
- Implemented value iteration
- Extracted the optimal policy
- Implemented policy iteration
- Implemented Q-Learning in a GridWorld environment
- Compared Random Agent and Q-Learning Agent performance
- Increased the GridWorld size from 8x8 to 15x15
- Observed changes in convergence and learning performance

## Question 2 - Model-Based vs Model-Free Reinforcement Learning

A comparison was performed between:

- Model-Based Reinforcement Learning using Policy Iteration
- Model-Free Reinforcement Learning using Q-Learning

Execution time and convergence behavior were observed and compared.

## Question 3 - Deep Q-Learning

A Deep Q-Learning model was implemented using a neural network to approximate Q-values.

The model was tested using different epsilon values:

- Epsilon = 0.1
- Epsilon = 0.5
- Epsilon = 0.9

The effect of exploration and exploitation on learning performance was observed using reward curves.

## Technologies Used

- Python
- Google Colab
- NumPy
- Matplotlib
- TensorFlow
- Keras

## Files

- `Markov_Decision_Process.ipynb` - MDP, Value Iteration and Policy Iteration implementations
- `Gridworld.ipynb` - Random Agent, Q-Learning and DQN implementations
- `IT23177482_DL_Lab08_Report.docx` - Lab report with screenshots, results and observations

## Conclusion

This lab demonstrated the differences between traditional reinforcement learning methods and Deep Q-Learning. Q-Learning was able to improve its performance through repeated interaction with the environment, while DQN used a neural network to approximate Q-values. The experiments also demonstrated the exploration-exploitation trade-off using different epsilon values.
