# Digit-Recognition

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to recognize handwritten digits from the MNIST dataset.

# Overview

The code performs the following steps:

Load and Preprocess Data:
Loads the MNIST dataset.
Reshapes and normalizes the data.

Build the CNN Model:
Constructs a CNN with two convolutional layers, max-pooling layers, a fully connected layer, and a dropout layer.

Compile and Train the Model:
Compiles the model with the Adam optimizer and sparse categorical cross-entropy loss.
Trains the model on the training data with validation on the test data.
Uses TensorBoard for visualization.

Evaluate and Save the Model:
Plots training and validation loss over epochs.
Saves the trained model to a file.

Load and Make Predictions:
Loads the saved model.
Makes predictions on the test data and visualizes a sample prediction.

# Requirements

Python 
TensorFlow 
Matplotlib
Seaborn
NumPy
Pandas
