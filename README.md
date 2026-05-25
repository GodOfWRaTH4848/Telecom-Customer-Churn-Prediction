# Telecom Customer Churn Prediction using Artificial Neural Networks

## Overview

This project develops and evaluates Artificial Neural Network (ANN) architectures to predict telecom customer churn.

The objective was to identify customers at high risk of churn, compare ANN model complexity against predictive performance, and generate business-oriented retention insights from customer behaviour patterns.

## Dataset
- Source: telco customer churn dataset
- Target: Churn (Yes/No)

## Tech Stack

- Python
- Pandas
- NumPy
- PyTorch
- Scikit-learn
- Matplotlib
- Seaborn

## Methods
- Preprocessing: Encoding categorical variables, feature engineering based on signal and correlation patterns
- Model: Feed-forward ANN with hidden layers
- Training: Backpropagation, activation functions (ReLU, GeLU, Sigmoid)
- Evaluation: Confusion matrix, Accuracy, Recall, F1
- Comparing ANN architectures and selecting the most practical deployment model

## Results
### ANN Model Comparison (Optimised Thresholds)

| Model | Threshold | Accuracy | Precision | Recall | F1 Score |
|---|---|---|---|---|---|
| ChurnANN (Complex) | 0.3 | 0.78 | 0.56 | 0.77 | 0.65 |
| SimpleANN | 0.4 | 0.81 | 0.63 | 0.69 | 0.66 |

### Key Observation

The simplified ANN achieved performance comparable to the deeper architecture while reducing overall model complexity.

Although the complex ANN achieved higher recall, the simpler model improved precision and overall accuracy while requiring fewer parameters and lower computational overhead.

This suggests that a lightweight ANN architecture may be more suitable for practical deployment in this churn prediction use case.

## How to Run
1. Clone the repo or download the notebook, then open in Google Colab or Jupyter.
2. Open in Google Colab or Jupyter Notebook.
3. Run cells. 

## Key Skills Demonstrated
- ANN architecture design
- Classification modeling
- Model evaluation
- Customer churn/ retention analytics
- Business recommendations based on churn behavior analysis
