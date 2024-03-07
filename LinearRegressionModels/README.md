# LinearRegressionModel

This repository contains implementations of two linear regression models using PyTorch. The models are built, trained, evaluated, and saved for future use.

## Table of Contents
1. [Data Preparation and Loading](#data-preparation-and-loading)
2. [Building the Models](#building-the-models)
3. [Training the Models](#training-the-models)
4. [Making Predictions and Evaluating the Models](#making-predictions-and-evaluating-the-models)
5. [Saving and Loading Models](#saving-and-loading-models)
6. [Putting It All Together](#putting-it-all-together)

## Data Preparation and Loading

The data is generated using known parameters (weight and bias) and prepared with a train/test split.

## Building the Models

Two linear regression models are built using PyTorch. One model is built from scratch with manual initialization of parameters, while the other utilizes PyTorch's built-in `nn.Linear()` module.

## Training the Models

The models are trained using stochastic gradient descent (SGD) with a specified learning rate. Loss values are tracked during training.

## Making Predictions and Evaluating the Models

Predictions are made using the trained models. Both training and test loss curves are plotted to evaluate model performance.

## Saving and Loading Models

Trained model parameters are saved to disk for future use. Models can be loaded and used for making predictions without needing to retrain.


