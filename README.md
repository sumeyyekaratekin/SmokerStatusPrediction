# Smoker Status Predictions

This project aims to develop a model for predicting an individual's smoking status using machine learning (ML) and artificial neural network (ANN) techniques. This README file provides an overview of the dataset, project files, and instructions for running the code.

## Dataset

The dataset used in this project is sourced from the [Kaggle Smoker Status ](https://www.kaggle.com/competitions/playground-series-s3e24/data) competition. It includes various demographic and health-related features to predict smoking status.

### Dataset Overview

The CSV files used for training are located in the `/res` directory.

- **train.csv**: Training data containing individual features and their smoking status.
- **test.csv**: Test data with individual features; smoking statuses need to be predicted.
- **sample_submission.csv**: A sample submission file that illustrates the required format for predictions.

## Project Files

The project consists of two main files:

1. **smokerStatus_ML.ipynb**: Contains code to train and evaluate a model using machine learning techniques. This file includes algorithms such as regression and classification methods.

2. **smokerStatus_ANN.ipynb**: Contains code to train and evaluate a model using artificial neural networks (ANN). This file focuses on deep learning and neural network configurations.

## Setup and Usage

### Requirements

To run this project, you will need the following Python packages:

- numpy
- pandas
- scikit-learn
- tensorflow
- keras

You can install the necessary packages using the following command:

```bash
pip install numpy pandas scikit-learn tensorflow keras
