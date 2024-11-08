# Neural Network Implementation: Perceptron and Adaline Models

This repository contains implementations of **Perceptron** and **Adaline (Adaptive Linear Neuron)** neural network models for binary classification tasks. The project explores various initialization techniques, learning rates, and configurations to optimize the models' performance on a handwritten character recognition dataset.

## Project Overview

This project demonstrates fundamental neural network models, focusing on the Perceptron and Adaline algorithms. It provides a hands-on approach to training, testing, and tuning these models, with a specific focus on understanding how initialization and learning rate affect performance.

- **Objective**: To classify characters accurately using simple neural network models.
- **Dataset**: A set of binary vectors representing pixel-based character images, where each vector represents a character class.

## Key Features

- **Perceptron Model**: A basic neural network model implementing binary classification through error-correction learning.
- **Adaline Model**: Similar to the Perceptron, but uses a linear activation function and minimizes the mean squared error (MSE) during training.
- **Weight Initialization Techniques**: Experimentation with various weight initialization methods to observe their effect on learning:
  - Zero initialization
  - Uniform and normal distribution initializations
  - Xavier (Glorot) initialization
  - Kaiming (He) initialization
- **Learning Rate Tuning**: Experimentation with different learning rates to optimize convergence.
- **Error Rate and MSE Calculation**: For performance evaluation, the Perceptron model uses error rate, while Adaline uses mean squared error as its primary metric.

## Repository Structure

- **Data**: Contains the dataset for training and testing.
- **Notebooks and Scripts**: Jupyter notebooks and Python scripts for:
  - Implementing and training the Perceptron and Adaline models
  - Testing and performance evaluation
  - Visualization of results
- **Results**: Documented results showing how different configurations impact model performance.

## Experimental Results

The project includes analyses of how weight initialization and learning rate adjustments affect the classification accuracy and mean squared error for each model. It highlights the conditions under which each model performs optimally.

## Getting Started

To run this project, clone the repository and install the dependencies listed in `requirements.txt`. You can then execute the provided Jupyter notebooks or Python scripts to train and test the Perceptron and Adaline models on the dataset.

```bash
git clone <repository-url>
cd <repository-folder>
pip install -r requirements.txt
