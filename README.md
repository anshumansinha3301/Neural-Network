# Neural-Network
This project is a Python-based implementation of a neural network built from scratch to classify handwritten digits,
likely using the MNIST dataset. It begins by loading the dataset and preprocessing it, which includes normalizing 
pixel values by scaling them between 0 and 1. The dataset is split into training and development sets to evaluate the model's performance.

The neural network architecture consists of two layers. The first is a hidden layer that uses the 
ReLU (Rectified Linear Unit) activation function to introduce non-linearity. The second is an output layer that 
applies the softmax activation function to generate probabilities for multi-class classification.

The project includes forward propagation, where the inputs are passed through the layers, and the output is computed.
It also handles one-hot encoding for the target labels and uses basic optimization techniques to update model parameters.
The model's performance is evaluated on both the training and development datasets, showcasing an end-to-end approach 
to building a neural network from scratch.
