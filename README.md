# Confusion Matrix Calculator

This Python project demonstrates how to compute and display the confusion matrix for binary classification using scikit-learn. A confusion matrix is a key evaluation tool that provides insights into the performance of classification models by visualizing the number of correct and incorrect predictions.

## Description

In this project, we use the `confusion_matrix` function from `scikit-learn` to generate a confusion matrix from a set of true labels (`y_true`) and predicted labels (`y_pred`). The confusion matrix provides the following information:

- **True Positives (TP)**: The number of positive instances correctly predicted as positive.
- **True Negatives (TN)**: The number of negative instances correctly predicted as negative.
- **False Positives (FP)**: The number of negative instances incorrectly predicted as positive.
- **False Negatives (FN)**: The number of positive instances incorrectly predicted as negative.

The matrix is represented as:

