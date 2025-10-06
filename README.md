# Function Approximation Using Neural Networks

## Project Overview

This project demonstrates how a neural network can learn complex mathematical relationships between input variables and output values. The network takes three input numbers and learns to predict the output of a specific mathematical function through training.


## How It Works

### Data Generation
The project creates synthetic training data by generating random combinations of three numbers (x, y, z) and computing their corresponding output values using a predefined mathematical function. This creates a dataset of 400 examples that the neural network uses for learning.

### Neural Network Architecture
The model is a fully connected neural network with the following layers:
- Input layer: 3 neurons (for x, y, z values)
- First hidden layer: 4 neurons with ReLU activation
- Second hidden layer: 3 neurons with ReLU activation
- Output layer: 1 neuron (for prediction)

### Training Process
The network learns through a process called backpropagation:
1. It makes predictions based on input data
2. Compares predictions with actual values using Mean Squared Error
3. Adjusts its internal parameters to minimize the error
4. Repeats this process over multiple epochs

## Installation

To run this project, you'll need:

```bash
pip install torch matplotlib numpy
