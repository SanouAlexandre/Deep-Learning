# MNIST Classification using Keras
This project demonstrates how to perform handwritten digit classification using 
the MNIST dataset with Keras, a high-level neural networks API running on top of 
TensorFlow.

# Overview
The MNIST dataset is a popular benchmark dataset in machine learning and computer 
vision. It consists of 28x28 grayscale images of handwritten digits (0-9) along 
with their corresponding labels.

In this project, we build and train neural network models to classify these images 
into their respective digit classes using Keras. We explore different network 
architectures, activation functions, optimizers, and training parameters to achieve 
optimal classification accuracy.

# Contents
mnist_classification_keras.ipynb: Jupyter Notebook containing the code for data loading, 
preprocessing, model definition, training, evaluation, and visualization of results.
README.md: Documentation providing an overview of the project, instructions for running 
the code, and insights into the results.
images: Directory containing images used in the README.md file.

# Requirements
Python 3.x
TensorFlow 2.x
Keras 2.x
NumPy
Matplotlib
Usage
Clone the repository to your local machine:

Follow the instructions in the notebook to execute the code cells, train the models, 
and visualize the results.

Results
The project evaluates various neural network architectures, activation functions, 
optimizers, and training parameters to classify MNIST digits. Here are some key results:

Achieved a test accuracy of over 98% with a fully connected neural network.
Visualized training and validation loss/accuracy curves to monitor model performance 
and detect overfitting.
Experimented with different network architectures, including varying hidden layer sizes
and activation functions.
Conducted experiments with different optimizers and batch sizes to optimize training 
efficiency and model performance.
