# German Credit Risk Analysis: Logistic Regression vs Random Forest

## Overview

This project compares Logistic Regression and Random Forest models using the German Credit Dataset to predict whether a customer is a good or bad credit risk.

## Objective

- Build and evaluate Logistic Regression and Random Forest models.
- Compare their performance using classification metrics.
- Identify the better model for credit risk prediction.

## Dataset

The German Credit Dataset contains information about loan applicants and their credit risk status.

- Records: 1,000
- Features: 20
- Target Variable: Risk (Good or Bad Credit)

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

## Machine Learning Workflow

```text
Data Preparation
      ↓
Encoding
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Prediction
      ↓
Evaluation
      ↓
Comparison
```

## Model Results

### Logistic Regression

| Metric | Score |
|----------|----------|
| Accuracy | 77.5% |
| Precision (Weighted Avg) | 0.76 |
| Recall (Weighted Avg) | 0.78 |
| F1-Score (Weighted Avg) | 0.76 |

### Random Forest

| Metric | Score |
|----------|----------|
| Accuracy | 80.5% |
| Precision (Weighted Avg) | 0.80 |
| Recall (Weighted Avg) | 0.81 |
| F1-Score (Weighted Avg) | 0.79 |

## Comparison

| Metric | Logistic Regression | Random Forest |
|----------|----------|----------|
| Accuracy | 77.5% | 80.5% |
| Precision | 0.76 | 0.80 |
| Recall | 0.78 | 0.81 |
| F1-Score | 0.76 | 0.79 |

## Key Findings

- Both models performed well in predicting credit risk.
- Random Forest achieved the highest accuracy (80.5%).
- Random Forest outperformed Logistic Regression across all evaluation metrics.
- Logistic Regression remains useful as a simple and interpretable baseline model.

## Conclusion

The results show that Random Forest provides better predictive performance than Logistic Regression for the German Credit Dataset. Based on accuracy, precision, recall, and F1-score, Random Forest is the preferred model for credit risk classification.

## Author

**Isaac Farai**

MBA Student | Data Analytics & Machine Learning
