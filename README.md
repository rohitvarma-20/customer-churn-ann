# Customer Churn Prediction using ANN

## Project Overview

This project predicts whether a customer is likely to churn using an Artificial Neural Network (ANN).

The project covers the complete machine learning workflow, including data preprocessing, categorical encoding, feature scaling, ANN model building, model training, validation, early stopping, prediction, and evaluation.

## Dataset

The dataset contains 1,000 customer records with information such as:

- Customer Age
- Tenure
- Monthly Charges
- Support Calls
- Contract Type
- Internet Service
- Payment Method
- Online Security
- Tech Support

### Target Variable

`churn`

- `0` → Customer stays
- `1` → Customer churns

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Jupyter Notebook

## Data Preprocessing

The following preprocessing steps were performed:

1. Separated features and target variable.
2. Encoded categorical features using One-Hot Encoding.
3. Split the data into training and testing sets.
4. Applied StandardScaler to numerical features.
5. Used validation data during model training.

## ANN Architecture

The neural network consists of:

```text
Input Layer: 13 Features
        ↓
Dense Layer: 16 Neurons + ReLU
        ↓
Dense Layer: 8 Neurons + ReLU
        ↓
Output Layer: 1 Neuron + Sigmoid
