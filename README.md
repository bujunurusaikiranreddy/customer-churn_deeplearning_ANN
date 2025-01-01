# Customer Churn Prediction Model

This repository contains a machine learning model for predicting customer churn.  The model is built using a neural network implemented with TensorFlow/Keras and trained on a customer churn dataset.

## Model Overview

The model utilizes a multi-layer perceptron (MLP) to classify customers as either likely to churn or not.  Preprocessing steps include handling missing values, one-hot encoding categorical features, and feature scaling.  Early stopping is used during training to prevent overfitting.

## Dataset

The model is trained on the "customer_churn" dataset (presumably from Hugging Face Datasets).  Key features include demographics, usage patterns, and customer engagement metrics.

## Dependencies

- pandas
- numpy
- matplotlib
- scikit-learn
- TensorFlow/Keras
