# Contextual Bandits: Advanced Decision-Making in Machine Learning

This repository contains implementations of various algorithms for solving the Contextual Bandit problem, an extension of the classic Multi-Armed Bandit problem. The code accompanies an article written on Medium about Contextual Bandits and their applications.

## Table of Contents

1. [Introduction](#introduction)
2. [Algorithms Implemented](#algorithms-implemented)
3. [Usage](#usage)
4. [Requirements](#requirements)
5. [Further Reading](#further-reading)

## Introduction

Contextual Bandits extend the Multi-Armed Bandit framework by incorporating additional contextual information that influences the rewards associated with each action. This project implements various algorithms to solve the Contextual Bandit problem, demonstrating different approaches to balancing exploration and exploitation while considering contextual information.

## Algorithms Implemented

1. **Epsilon-Greedy Algorithm** (`Epsilon_Greedy_Contextual.ipynb`)
2. **Upper Confidence Bound (UCB)** (`UCB_Contextual.ipynb`)
3. **Thompson Sampling** (`Thompson_Sampling_Contextual.ipynb`)

Each algorithm is implemented in a separate Jupyter notebook for easy understanding and experimentation.


## Usage

To use these implementations:

1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed.
3. Navigate to the `Contextual_Bandits` directory.
4. Open the notebook in Jupyter Notebook or Google Colab.
5. Run the cells in the notebook to see the algorithm in action.


## Requirements

- Python 3.x
- Jupyter Notebook
- NumPy
- Matplotlib (for visualizations)
- PyTorch (for implementation)

You can install the required packages using pip:

```
pip install jupyter numpy matplotlib torch
```

## Further Reading

For a detailed explanation of Contextual Bandits and these algorithms, please refer to the accompanying [Medium article](https://medium.com/@kapardhikannekanti/understanding-contextual-bandits-advanced-decision-making-in-machine-learning-85c7c20417d7).

Additional resources:
- [Simple Reinforcement Learning with TensorFlow](https://awjuliani.medium.com/simple-reinforcement-learning-with-tensorflow-part-1-5-contextual-bandits-bff01d1aad9c)
- [Contextual Bandits and Reinforcement Learning](https://hunch.net/~exploration_learning/)
- [MWT White Paper](https://www.microsoft.com/en-us/research/group/multi-world-testing/)

Feel free to experiment with the code, modify parameters, and observe how different algorithms perform under various contextual scenarios.

If you have any questions or suggestions, please open an issue in this repository or contact the author at kapardhikannekanti@gmail.com.

Happy exploring and exploiting in context!