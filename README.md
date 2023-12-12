# Ocular Disease Recognition - Cataract Classification

## Overview
This repository contains a Python script for Ocular Disease Recognition using PyTorch and EfficientNet models. The script includes data loading, sample transformations, model preparation, training, and evaluation functions.

## Dataset
The Ocular Disease Recognition dataset is used in this script from [Kaggle](https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k)

![image](https://github.com/aziegert/Cataract_Classification_CV/assets/123495041/01706a5f-9678-4c42-8888-322dda910287)

## Sample Transformations
Various image transformations are applied to augment the dataset, including color jitter, equalization, horizontal flip, grayscale, and random invert. These transformations are visualized to show the original image and it's transformations.
![image](https://github.com/aziegert/Cataract_Classification_CV/assets/123495041/d65653f7-8942-4373-8e30-9442718c3130)


## Model Preparation
To creating model used pretrained EfficientNet architectures.

## Selecting
Here key components are selected that affect the operation of classification models, such as:
- model architecture
- activation function in the last classification layer
- image transformations are applied to augment the dataset
- batch size
- learning rate scheduler

This process aims to identify optimal model settings and hyperparameters to improve model performance.

## Training model
Training several models based on pre-trained EfficientNet architectures (B0 to B3) to create an ensemble model through their aggregation.
![image](https://github.com/aziegert/Cataract_Classification_CV/assets/123495041/0b08a8d8-1a60-4902-88d0-a9e49d41c94a)

## Prediction for test data
The prediction module consists of two fundamental functions: test_model and predict_average_model, designed for evaluating and predicting for test data.
![image](https://github.com/aziegert/Cataract_Classification_CV/assets/123495041/22d68f2d-8c32-446d-84be-0ca7b9efb78a)


## Sample predictions
Visualiztion for sample predictions.
![image](https://github.com/aziegert/Cataract_Classification_CV/assets/123495041/fe9b4fe3-d140-4350-8fb4-0781a69af574)
