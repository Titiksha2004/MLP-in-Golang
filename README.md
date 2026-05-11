# Multilayer Perceptron from Scratch in Golang

A custom implementation of a Multilayer Perceptron (MLP) neural network built entirely from scratch in Golang without using external machine learning frameworks. This project demonstrates the core fundamentals of neural networks, including forward propagation, backpropagation, gradient descent, and supervised learning.

---

# Overview

This project explores the internal mechanics of artificial neural networks by implementing a fully connected feedforward neural network in Go.

The implementation includes:
- Custom neuron and neural layer structures
- Forward propagation
- Backpropagation algorithm
- Gradient descent optimization
- Weight and bias updates
- Support for multi-class classification

The goal of this project was to understand how neural networks operate internally rather than relying on high-level libraries such as TensorFlow or PyTorch.

---

# Features

## Neural Network from Scratch
- No external deep learning libraries used
- Fully custom neural network architecture
- Manual implementation of training algorithms

## Multilayer Perceptron (MLP)
- Input layer
- Hidden layer(s)
- Output layer
- Configurable network architecture

## Forward Propagation
- Input data flows layer-by-layer through the network
- Weighted sums and activation functions generate predictions

## Backpropagation
- Computes output and hidden layer errors
- Calculates gradients using activation function derivatives
- Updates weights and biases iteratively

## Gradient Descent Optimization
- Uses learning rate-based optimization
- Minimizes prediction error over multiple epochs

## Multi-Class Classification Support
- Supports one-hot encoded outputs
- Handles classification problems with multiple classes

---

# Tech Stack

| Technology | Purpose |
|---|---|
| Golang | Core implementation |
| Standard Library | Mathematical operations and data structures |

---

# Neural Network Architecture

The project implements a fully connected feedforward neural network.

```text
Input Layer
     ↓
Hidden Layer(s)
     ↓
Output Layer
