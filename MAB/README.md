# Multi-Armed Bandit (MAB) Problem Implementations

This repository contains implementations of various algorithms for solving the Multi-Armed Bandit (MAB) problem. The code accompanies an article written on Medium about the MAB problem and its solutions.

## Table of Contents

1. [Introduction](#introduction)
2. [Algorithms Implemented](#algorithms-implemented)
3. [File Structure](#file-structure)
4. [Usage](#usage)
5. [Requirements](#requirements)
6. [Further Reading](#further-reading)

## Introduction

The Multi-Armed Bandit problem is a classic problem in decision theory and reinforcement learning. It models an agent that simultaneously attempts to acquire new knowledge (called "exploration") and optimize their decisions based on existing knowledge (called "exploitation").

This project implements various algorithms to solve the MAB problem, demonstrating different approaches to balancing exploration and exploitation.

## Algorithms Implemented

1. **Greedy Algorithm** (`MAB_Greedy.ipynb`)
2. **Epsilon-Greedy Algorithm** (`Epsion_Greedy.ipynb`)
3. **Upper Confidence Bound (UCB)** (`UCB.ipynb`)
4. **Thompson Sampling** (`Thompson_Sampling_MAB.ipynb`)

Each algorithm is implemented in a separate Jupyter notebook for easy understanding and experimentation.

## File Structure

```
MAB/
│
├── MAB_Greedy.ipynb
├── Epsion_Greedy.ipynb
├── UCB.ipynb
├── Thompson_Sampling_MAB.ipynb
└── README.md
```

## Usage

To use these implementations:

1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed.
3. Navigate to the `MAB` directory.
4. Open the desired notebook (e.g., `MAB_Greedy.ipynb`) in Jupyter Notebook.
5. Run the cells in the notebook to see the algorithm in action.

Each notebook contains explanations, code implementations, and possibly visualizations to help understand how the algorithms work.

## Requirements

- Python 3.x
- Jupyter Notebook
- NumPy
- Matplotlib (for visualizations, if included)

You can install the required packages using pip:

```
pip install jupyter numpy matplotlib
```

## Further Reading

For a detailed explanation of the Multi-Armed Bandit problem and these algorithms, please refer to the accompanying [Medium article](https://medium.com/@kapardhikannekanti/everything-you-need-to-know-about-the-multi-armed-bandit-cdd0c85a9835).


Feel free to experiment with the code, modify parameters, and observe how different algorithms perform under various conditions.

If you have any questions or suggestions, please open an issue in this repository.

Happy exploring and exploiting!