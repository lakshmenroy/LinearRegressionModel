# FashionMNIST Classification Models

This repository contains three PyTorch models for classifying FashionMNIST dataset.

## Models Overview

### Model 1
- **Name:** FashionMNISTModelV0
- **Description:** Basic feedforward neural network model.
- **Architecture:** 
  - Input layer: Flatten layer
  - Hidden layer: Linear layer with 10 units
  - Output layer: Linear layer with output units equal to the number of classes
- **Training Procedure:** Trained using stochastic gradient descent (SGD) optimizer with cross-entropy loss.
- **Evaluation Results:** Achieved an accuracy of [83.42651757188499] on the test dataset.

### Model 2
- **Name:** FashionMNISTModelV1
- **Description:** Neural network model with non-linear activation functions.
- **Architecture:** 
  - Input layer: Flatten layer
  - Hidden layer: Linear layer with ReLU activation function
  - Output layer: Linear layer with ReLU activation function
- **Training Procedure:** Trained using SGD optimizer with cross-entropy loss.
- **Evaluation Results:** Achieved an accuracy of [76.46765175718849] on the test dataset.

### Model 3
- **Name:** FashionMNISTModelV2
- **Description:** Convolutional neural network (CNN) model based on TinyVGG architecture.
- **Architecture:** 
  - Block 1:
    - Convolutional layer with ReLU activation
    - Convolutional layer with ReLU activation
    - Max pooling layer
  - Block 2:
    - Convolutional layer with ReLU activation
    - Convolutional layer with ReLU activation
    - Max pooling layer
  - Classifier:
    - Flatten layer
    - Linear layer
- **Training Procedure:** Trained using SGD optimizer with cross-entropy loss.
- **Evaluation Results:** Achieved an accuracy of [88.26876996805112] on the test dataset.

## Instructions for Running the Models

1. Ensure you have Python and PyTorch installed.
2. Clone this repository to your local machine.
3. Navigate to the directory containing the models.
4. Run the appropriate script for each model (e.g., `python model_1.py`).

## Additional Notes

- The dataset used for training and evaluation is FashionMNIST.
- Make sure to check the requirements and compatibility of PyTorch and torchvision versions.
- For detailed implementation and usage, refer to the individual model scripts.
