# Binary and Multiclass Classification Models

This repository contains Python code for two different classification tasks:

1. **Binary Classification Model**: This model is trained to classify data into two classes. It utilizes a neural network architecture built using PyTorch to fit a binary classification dataset generated using the `make_moons` function from Scikit-Learn.

2. **Multiclass Classification Model**: This model is designed to classify data into multiple classes. It employs a similar neural network architecture as the binary classification model but is trained on a spiral dataset generated using the `spirals` function from CS231n.

## Dependencies
- Python 3.x
- PyTorch
- NumPy
- Matplotlib
- Scikit-Learn

## Instructions

### 1. Setting Up the Environment
- Ensure that you have Python installed on your system.
- Install the required dependencies using pip:
```python
# Install dependencies
!pip install torchmetrics
!pip install torch
!pip install numpy
!pip install matplotlib
!pip install scikit-learn
```
### 2. Running the Code
- The code is organized into two separate Python scripts: `binary_classification.py` and `multiclass_classification.py`.
- Execute each script to run the respective classification model.
- The training process and model evaluation will be displayed in the console output.
- After training, decision boundaries for both the training and test sets will be plotted to visualize the model's performance.

## Files Included
- `binary_classification.py`: Python script for training and evaluating the binary classification model.
- `multiclass_classification.py`: Python script for training and evaluating the multiclass classification model.
- `README.md`: Markdown file containing instructions and information about the repository.

