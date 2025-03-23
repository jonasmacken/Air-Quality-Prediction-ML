# air-quality-prediction-ml

This project uses deep learning to model and predict air quality based on historical data. It includes both a regression model (predicting exact pollution levels) and a binary classification model (predicting whether air quality will be above a threshold).

---

## Problem Statement

Using hourly chemical and environmental data (such as CO, NOx, NO₂, and temperature), the objective is to:

-  Predict continuous air quality values (regression)
-  Classify whether the pollution level is above the average (binary classification)

---

## Model Architectures

### 1. Classification Model

A binary classifier using a feedforward neural network with dropout and L2 regularisation:

- 2 hidden layers (ReLU)
- Dropout (0.5) for regularisation
- L2 regularisation
- Sigmoid output layer
- Binary cross-entropy loss
- Metrics: Accuracy, Precision

### 2. Regression Model

A simple feedforward neural network:

- 2 hidden layers (ReLU)
- Linear output layer
- Mean Squared Error loss
- Metrics: MAE, RMSE (custom)

---

## Repository Structure

├── air_quality_prediction.ipynb      # Jupyter notebook with code, results, and analysis
├── AirQualityUCI_Students.xlsx       # Original training dataset
├── Generalization_Dataset.xlsx       # Additional dataset for testing/generalization
├── README.md                         # Project documentation
└── requirements.txt                  # List of Python dependencies                        

