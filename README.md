# Multilayer Perceptrons: Impact of Hidden Layer Depth on Neural Network Performance

This repository contains the code and tutorial for the machine learning assignment investigating how hidden layer depth affects the performance of Multilayer Perceptrons (MLPs) using the Fashion-MNIST dataset.

## Project Overview

Neural network architecture plays an important role in determining model performance. In particular, the number of hidden layers can significantly influence the ability of a neural network to learn complex patterns.

This tutorial investigates how increasing hidden layer depth affects classification accuracy, training behaviour, and model generalisation.

The experiments are conducted using the Fashion-MNIST dataset, a benchmark dataset for image classification tasks.

## Dataset

The Fashion-MNIST dataset consists of 70,000 grayscale images of clothing items belonging to 10 classes.

Dataset split:

- Training samples: 60,000
- Test samples: 10,000
- Image resolution: 28 × 28 pixels

## Experiment

Five Multilayer Perceptron architectures were trained with different hidden layer depths:

- 1 hidden layer
- 2 hidden layers
- 3 hidden layers
- 4 hidden layers
- 5 hidden layers

Each hidden layer contains 128 neurons with ReLU activation.

Training configuration:

- Optimizer: Adam
- Loss function: Sparse categorical crossentropy
- Epochs: 10
- Batch size: 128
