# ANN-with-Momentum
Artificial Neural Networks with Back Propagation and Momentum (Without using keras and tensorflow)

## Steps
1. Import necessary libraries
  - numpy
  - matplotlib
  - glob
  - cv2
  - random
  - os

1. Download and preprocess the dataset
  - Load Training and Test Datasets
  - Shuffle Training and Test Datasets
  - Resize and Normalize the images

1.  Initialize random weights and biases
  - Create dictionary to store weights and biases
  - Initialize weights and biases to zero for backpropagation

1. Fix all hyperparameters
  - Learning rate
  - Number of epochs
  - Number of layers
  - Number of units in each layer
  - Momentum (𝛂)

1. Until the termination condition is met, Do
  - For each training example, Do
  - **Forward Propagation:** Calculate the output of each unit and propagate through the layers.
  - **Backward Propagation:**	Calculate the errors (for output and hidden units). Calculate the change in weights & biases. Add the momentum and update the weights & biases.

**Note:** This is a project done for Machine Learning Course (Team of 4)
