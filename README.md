# Predict Titanic Survival - Classification Model

## Overview

This project is Task 3 of the Neurofive ML Track. The goal is to build a first classification model capable of predicting whether a Titanic passenger survived.

## Dataset

Titanic - Machine Learning from Disaster dataset.

## Approach

1. Loaded the Titanic dataset
2. Handled missing values
3. Selected relevant features
4. Encoded categorical variables using `pd.get_dummies()`
5. Split the data using `train_test_split()`
6. Trained a Logistic Regression model
7. Generated predictions
8. Evaluated the model using accuracy
9. Analyzed the results using a confusion matrix

## Model

**Algorithm:** Logistic Regression

## Evaluation

The model achieved approximately **80% accuracy** on the test set.

## Confusion Matrix

The confusion matrix was used to identify:

- True Positives
- True Negatives
- False Positives
- False Negatives

This provides more information about the model's mistakes than accuracy alone.

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Author

Laiba Nasir
