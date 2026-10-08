# Aurora Visibility Prediction Using Neural Networks

## Project Overview

This project explores binary classification using a small neural network built with TensorFlow/Keras.

The goal is to predict April aurora visibility categories for different geographic locations using location-based and geomagnetic features.

This is an introductory machine learning experiment and a foundation for further research into neural network optimization and explainability.

## Dataset

The dataset contains 69 aurora-viewing destinations and includes geographic coordinates, geomagnetic latitude, minimum Kp index, and monthly visibility scores.

The visibility values are compiled planning scores rather than observed aurora events.

## Technologies

- Python
- pandas
- scikit-learn
- TensorFlow/Keras
- Matplotlib
- Google Colab

## Model Architecture

- Input layer: 4 features
- Hidden layer 1: 8 neurons, ReLU
- Hidden layer 2: 4 neurons, ReLU
- Output layer: 1 neuron, Sigmoid

The model uses the Adam optimizer and binary cross-entropy loss.

## Initial Results

| Metric | Result |
|---|---|
| Training accuracy | 100% |
| Validation accuracy | 90.91% |
| Test accuracy | 78.57% |
| Test samples | 14 |

These are preliminary results from a very small dataset and should not be interpreted as evidence of real-world aurora forecasting performance.

## Future Work

- Improve data splitting and preprocessing
- Compare neural network architectures
- Evaluate models using cross-validation
- Investigate feature attribution methods such as SHAP
- Study the trade-off between predictive performance and explanation stability

## Dataset Attribution

Dataset source and license details to be added after verification.
