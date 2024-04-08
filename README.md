# Neural Network Logic Gates

This Python project illustrates how to implement simple neural networks to emulate the functionality of basic logical gates: AND and OR. Utilizing the scikit-learn library's MLPClassifier, a type of Multi-layer Perceptron classifier, the project provides a hands-on example of how even straightforward neural networks can learn to perform logical operations based on binary input.

## Features

- **Simple yet Powerful**: Demonstrates the power of neural networks using minimalistic examples.
- **Dual Logic Gate Simulation**: Includes implementations for both AND and OR logical operations.
- **Comprehensive Learning and Prediction**: Showcases the process of training neural networks on a dataset and using them for prediction.

## Requirements

To run this project, you'll need:

- Python 3.x
- scikit-learn
- numpy

These dependencies can be installed via pip:

```bash
pip install numpy scikit-learn


The core of the project lies in its simplicity and straightforward approach:

Data Preparation: Inputs (X) and outputs (Y_and for AND, Y_or for OR) datasets are prepared to represent all possible combinations of binary inputs and their respective logical outputs.

Model Configuration and Training: Two MLPClassifier models are set up with specific configurations—using a single hidden layer with one neuron, the stochastic gradient descent solver, and an identity activation function. Each model is then trained on its corresponding dataset.

Testing and Prediction: The trained models are tested with the input dataset to predict the outcomes of the AND and OR operations, demonstrating the neural networks' ability to learn and mimic these logical functions.

Code Structure
logical_operations_nn.py: The main script where the neural networks are defined, trained, and evaluated.
Contributing
Feel free to fork this project, submit pull requests, or suggest improvements via issues.
