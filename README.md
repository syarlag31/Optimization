# Modernized Learning Rate Schedules in Optimization

## Overview

This project explores advanced learning rate schedules in optimization methods, particularly focusing on modern approaches that can accelerate convergence in gradient descent algorithms. The study is rooted in our research paper titled "Modernized View of Learning Rates in Optimization Methods" and is supplemented by experimental analyses through various machine learning models.

## Key Concepts

- **Gradient Descent with Long Steps**: Investigates the impact of integrating long step sizes into the gradient descent cycle, challenging traditional notions of monotonic convergence.
- **Cyclical Step-Sizes**: Explores the cyclical variation of step sizes to exploit the spectral gaps in the Hessian matrix, enhancing the convergence rates.
- **Chebyshev Fractal Learning Rate Schedules**: Utilizes Chebyshev polynomials to derive non-monotonic learning rate schedules, aiming to improve the stability and speed of convergence.

## Repository Contents

- `Paper.pdf`: The detailed research paper discussing the theoretical background, methodologies, and insights from our study.
- `Experiments.ipynb`: Jupyter notebook containing all the experiments conducted as part of this research. It includes implementations of various learning rate schedules on benchmark datasets like CIFAR-10, MNIST, and California Housing.

## Running the Experiments

To run the experiments in `Experiments.ipynb`, follow these steps:

1. Ensure you have Python and Jupyter Notebook installed on your system.
2. Install required libraries using `pip install -r requirements.txt`
3. Open the notebook in Jupyter Notebook or JupyterLab and run the cells sequentially.

## Experimental Results

The experiments demonstrate the effectiveness of innovative learning rate strategies over traditional methods, with particular success in complex datasets:

- Enhanced training stability and performance in deep learning models.
- Fractal and cyclical learning rate schedules showing significant improvements in convergence speed.
