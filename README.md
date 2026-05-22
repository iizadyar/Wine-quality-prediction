# Wine quality prediction

This project predicts wine quality using machine learning models on the UCI Wine Quality dataset. The dataset was modeled as both a regression and classification problem.

## Dataset

The red wine dataset was used:

https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv

The target variable is `quality`.

## Methods

### Regression

ElasticNet regression was used to predict wine quality as a numerical score.

Metric:

- RMSE

### Classification

Wine quality was treated as a class label.

Models used:

- Logistic Regression
- K-Nearest Neighbors

Metric:

- Accuracy

## Results

| Model | Task | Train Result | Test Result |
|---|---|---:|---:|
| ElasticNet | Regression | RMSE = 0.81 | RMSE = 0.77 |
| Logistic Regression | Classification | Accuracy = 0.60 | Accuracy = 0.60 |
| K-Nearest Neighbors | Classification | Accuracy = 0.67 | Accuracy = 0.61 |

## Visualization

<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/e1b9a903-6972-4746-acf0-c6ccc2b97835" />


## Requirements

```text
pandas
numpy
scikit-learn
matplotlib
