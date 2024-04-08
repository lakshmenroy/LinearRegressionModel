# Custom Dataset Models for Image Classification

This repository contains two PyTorch models for image classification trained on custom datasets.

## Model Architectures

### Model 0
- **Name:** TinyVGG_Model0
- **Description:** Basic convolutional neural network (CNN) model with two convolutional blocks and a classifier.
- **Architecture:** 
  - Convolutional Block 1:
    - Convolutional layer (kernel_size=3, stride=1, padding=0) followed by ReLU activation
    - Convolutional layer (kernel_size=3, stride=1, padding=0) followed by ReLU activation
    - Max pooling layer (kernel_size=2, stride=2)
  - Convolutional Block 2:
    - Convolutional layer (kernel_size=3, stride=1, padding=0) followed by ReLU activation
    - Convolutional layer (kernel_size=3, stride=1, padding=0) followed by ReLU activation
    - Max pooling layer (kernel_size=2, stride=2)
  - Classifier:
    - Flatten layer
    - Linear layer
- **Training Procedure:** Trained on custom dataset using stochastic gradient descent (SGD) optimizer.
- **Initialization:** Random initialization of weights.
- **Evaluation Results:** To be filled after evaluation.

### Model 1
- **Name:** TinyVGG_Model1
- **Description:** Similar to Model 0 but trained with augmented data using TrivialAugmentWide.
- **Architecture:** 
  - Same as Model 0
- **Training Procedure:** Trained on augmented custom dataset using stochastic gradient descent (SGD) optimizer.
- **Initialization:** Random initialization of weights.
- **Evaluation Results:** To be filled after evaluation.

## Additional Notes

- The models were trained and evaluated on custom datasets.
- Adjust hyperparameters and training configurations in the respective training scripts as needed.
- For detailed implementation and usage, refer to the individual model scripts.
