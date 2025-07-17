# Logistic Regression From Scratch on Heart Disease Dataset

This project implements Logistic Regression from scratch (using only libraries like NumPy for basic operations) on the Heart Disease dataset.
The goal was to train and evaluate the model without using any built‑in machine learning training functions.

## Dataset
The dataset used is the **Heart Disease** dataset.
It was split into:
- 70% for training
- 15% for testing
- 15% for validation

## Methods Implemented

### 1. Batch Gradient Descent
- Implemented Logistic Regression with batch gradient descent.
- Plotted:
  - Training loss vs iteration
  - Validation loss vs iteration
  - Training accuracy vs iteration
  - Validation accuracy vs iteration
- Compared and analyzed convergence from these plots.

### 2. Feature Scaling
- Compared model performance with:
  - Min-max scaling
  - No scaling
- Plotted loss vs iteration for each method.
- Discussed how scaling affects convergence.

### 3. Confusion Matrix and Metrics
- Calculated confusion matrix on the validation set.
- Reported:
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC Score
- Discussed what these metrics mean for the model’s performance.

### 4. Different Optimization Algorithms
- Implemented and compared:
  - Stochastic Gradient Descent
  - Mini-Batch Gradient Descent (with different batch sizes)
- Plotted and compared:
  - Loss vs iteration
  - Accuracy vs iteration
- Discussed trade-offs in convergence speed and stability.

### 5. K-Fold Cross Validation
- Performed 5-fold cross validation.
- Reported average and standard deviation for:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- Discussed stability and variance across folds.

### 6. Early Stopping
- Implemented early stopping in the best gradient descent method.
- Tried different learning rates and regularization (L1 and L2).
- Compared performance with and without early stopping.
- Analyzed effect of early stopping on overfitting and generalization.

## How to Run
1. Load the dataset (Heart Disease dataset in CSV format).
2. Run the Python scripts step by step.
3. Make sure you have NumPy, Matplotlib, Sklearn

## Results
- Plots show how the model converges with different methods.
- Feature scaling helps the model converge faster and more stably.
- Confusion matrix and metrics give insight into model performance.
- Mini-batch gradient descent offers a balance between speed and stability.
- K-fold cross validation shows the model’s robustness.
- Early stopping helps avoid overfitting and improves generalization.

