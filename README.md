# PyTorch-MNIST-Classifier

A project exploring neural networks and deep learning concepts. This repository contains code for training and evaluating a neural network on the MNIST dataset. Key features include:
- Data loading, preprocessing, and splitting (train, validation, test).
- Implementation of a feed-forward neural network using PyTorch.
- Model training using the Rprop optimization algorithm.
- Hyperparameter tuning using K-fold cross-validation and random search.
- Evaluation metrics including accuracy, loss, confusion matrix, and classification report.
- Early stopping mechanism to prevent overfitting.
- Visualization of training progress and results.

## Requirements

- Linux operating system
- An Nvidia GPU compatible with the latest CUDA version

## Set-up (Linux)

- Update system packages:
  - `sudo apt update && sudo apt upgrade`
- Install build-essential and CUDA dependencies:
  -  `sudo apt install build-essential nvidia-cuda-toolkit`
  - If you are using WSL or other platforms install the CUDA dependencies from the official [website](https://developer.nvidia.com/cuda-toolkit)
- Create a new python virtual environment in the project direcory:
  -  `python -m venv .venv` 
- Activate the virtual environment:
  - `source .venv/bin/activate`
- Install the required packages: 
  - `pip install -r requirements.txt`, this will install the required packages