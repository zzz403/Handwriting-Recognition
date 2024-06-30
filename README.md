# Handwriting-Recognition

This project is a simple handwritten digit classifier using PyTorch and the MNIST dataset. The classifier is a neural network model that learns to recognize and classify handwritten digits (0-9) through supervised learning.

## Purpose

The purpose of this project is to demonstrate the process of building, training, and evaluating a neural network for digit classification. This project was created as part of my machine learning coursework to showcase my understanding of machine learning and neural networks.

## How It Works

The neural network model is defined in PyTorch, and it consists of four fully connected layers. The model is trained using the MNIST dataset, which contains 60,000 training images and 10,000 test images of handwritten digits.

### Model Architecture

1. **Input Layer**: 28x28 pixels, flattened into 784 nodes.
2. **Hidden Layers**: Three hidden layers, each with 64 nodes and ReLU activation.
3. **Output Layer**: 10 nodes with log-softmax activation, representing the digit classes (0-9).

### Training Process

1. **Data Loading**: The MNIST dataset is loaded and transformed into tensors.
2. **Model Initialization**: The neural network model is created.
3. **Evaluation**: Initial accuracy of the model is evaluated on the test set.
4. **Training**: The model is trained for 2 epochs using the Adam optimizer and negative log-likelihood loss function.
5. **Evaluation**: Accuracy of the model is evaluated after each epoch.
6. **Visualization**: The first four test images are displayed with their predicted labels.

## Getting Started

### Prerequisites

- Python 3.x
- PyTorch
- torchvision
- matplotlib
