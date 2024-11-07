# Perceptron Model for Handwritten Character Recognition

This repository contains an implementation of a **Perceptron neural network model** designed for binary classification, specifically targeting a handwritten character recognition task. The project explores different initialization techniques and parameter configurations to optimize the model's classification accuracy.

## Project Overview

This project is inspired by exercises on artificial neural networks, focusing on implementing the fundamental Perceptron model and evaluating its performance on a character recognition task.

- **Objective**: Train and test the Perceptron model on a small dataset of pixel-based binary vectors, each representing a character, to classify them accurately.
- **Dataset**: The dataset consists of character images represented as binary vectors, with each pixel's value determining the character's classification.

## Key Features

- **Perceptron Model**: Implementation of the Perceptron algorithm, emphasizing learning through error correction.
- **Custom Weight Initialization**: Experimentation with different initialization methods to study their effect on learning:
  - Zero initialization
  - Random initialization (uniform and normal distributions)
  - Xavier (Glorot) initialization
  - Kaiming (He) initialization
- **Thresholding and Activation**: Custom activation functions and threshold adjustments to handle binary classification.
- **Error Rate Calculation**: A metric to evaluate model performance, reporting error rates on both training and testing datasets.

## Repository Structure

- **Data**: Contains the dataset for training and testing.
- **Notebooks and Scripts**: Jupyter notebooks and Python scripts for:
  - Implementing the Perceptron model
  - Training and testing routines
  - Performance evaluation and visualization
- **Results**: Documentation of model performance under various configurations.

## Experimental Results

The project includes a detailed analysis of how different weight initialization techniques and learning rates impact the Perceptron's classification accuracy. The results highlight the effectiveness of each initialization approach in reducing classification errors.


