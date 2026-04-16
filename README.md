# Liver Disease Prediction from Scratch

### Project Overview
This project implements a binary classification model to predict liver disease based on clinical records. Unlike standard library-based implementations, this model was built **from scratch** using Gradient Ascent to understand the optimization mechanics of Logistic Regression.

### Dataset
The data consists of 583 patient records from the North-East region of Andhra Pradesh. Features include various bilirubin levels, liver enzymes, and protein ratios.

### Mathematical Approach
- **Optimization**: Batch Gradient Ascent
- **Hypothesis**: Sigmoid/Logistic Function
- **Enhancement**: Implementation of an **intercept (bias) term**, which improved model accuracy from 60% to 75%.

### Key Results
- **Accuracy**: 75.2%
- **Recall**: 93.9%

The high recall indicates the model is highly sensitive to disease, making it a potentially useful screening tool in a clinical environment.
