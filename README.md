# Multilayer Neural Network for Advertising Sales Analysis

## Overview

This repository contains a Python implementation of a Multilayer Neural Network (MLP) to analyze and predict sales data
from an advertising dataset. The neural network is built using Keras, a high-level neural networks API written in
Python. The goal is to demonstrate how a feedforward neural network can be used for regression tasks, specifically
predicting sales based on advertising features.

## Table of Contents

- [Dataset](#dataset)
- [Neural Network Architecture](#neural-network-architecture)
- [Getting Started](#getting-started)
- [Results and Evaluation](#results-and-evaluation)

## Dataset

The dataset used in this project is an advertising dataset containing information about advertising spending and sales
data. It includes features such as 'digital', 'TV', 'radio', and 'newspaper' advertising expenses, and the
corresponding 'sales' data. The dataset is loaded from a CSV file hosted on GitHub.

## Neural Network Architecture

The neural network implemented in this project is a feedforward neural network with multiple layers:

- Input Layer: The input layer takes four features as input, representing the advertising expenses.
- Hidden Layers: The network consists of two hidden layers with 4 and 3 nodes, respectively. Both layers use the ReLU
  activation function.
- Output Layer: The output layer has a single node, which predicts the sales value.

## Getting Started

To run the code in this repository, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/your_username/multilayer-neural-network-sales-analysis.git
   ```
2. Install the required Python libraries by running:
   ```
   pip install tensorflow pandas numpy matplotlib seaborn sklearn
   ```
3. Open the Jupyter Notebook or Python script and execute the code step by step.

## Results and Evaluation

The code includes various visualizations and evaluations to understand the performance of the neural network:

- Correlation Heatmap: Visualizes the correlation between different features and sales.
- Scatter Plots: Shows the relationship between each feature and sales.
- Model Loss Graph: Plots the training and validation loss during the training process.
- Predicted vs. True Values: Compares the predicted sales values with the actual sales values.
- Mean Squared Error: Calculates the MSE for both training and testing data.
