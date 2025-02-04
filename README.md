# Water Potability classification model

## Overview

This project aims to develop a machine learning model to predict the potability of water based on various water quality parameters.
The model is built using TensorFlow/Keras and employs a combination of regularization and optimization techniques to achieve accurate predictions.

## Dataset

To create the water potability classification model, [dataset](https://drive.google.com/file/d/1VXHjV4Hi7d__I9v2KYudh32OVud3aEvm/view) was used. The
dataset contains 9 columns of data with variables or parameters that affect the potability(quality) of water. The target variable is the potability of
the water, which is a binary classification.

## Model Architecture and Optimization Techniques

| Train Instance | Engineer Name | Regularizer | Optimizer | Early Stopping | Dropout Rate | Accuracy | F1 Score | Recall | Precision |
|----------------|---------------|-------------|-----------|----------------|--------------|----------|----------|---------|-----------|
|prediction_model|Bernice Uwituze|L2 regularization|Adam   | Patience=10    |              |          |          |         |           |
