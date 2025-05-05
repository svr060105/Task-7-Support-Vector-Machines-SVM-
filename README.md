# Support Vector Machines (SVM) - Binary Classification

This project demonstrates how to use Support Vector Machines (SVM) for both **linear** and **non-linear (RBF)** classification using the **Breast Cancer dataset**. It includes training, visualization, hyperparameter tuning, and performance evaluation.

---

## Objective

- Apply SVMs for binary classification.
- Visualize decision boundaries using 2D PCA.
- Tune hyperparameters like `C` and `gamma`.
- Use cross-validation to evaluate model performance.

---

## Tools & Libraries

- Python
- Scikit-learn
- NumPy
- Matplotlib

---


## Project Workflow

### 1. Load and Prepare the Dataset
- Load dataset using `load_breast_cancer()` from Scikit-learn.
- Split into training and test sets.
- Standardize features using `StandardScaler`.

### 2. Train SVM Classifiers
- Train an SVM with **linear kernel**.
- Train an SVM with **RBF (non-linear) kernel**.
- Evaluate using accuracy on test set.

### 3. Visualize Decision Boundaries
- Reduce dimensionality to 2D using PCA.
- Plot decision boundaries for both linear and RBF models.

### 4. Hyperparameter Tuning
- Use `GridSearchCV` to tune `C` and `gamma` for the RBF kernel.
- Perform 5-fold cross-validation.

### 5. Model Evaluation
- Predict on test set with the best model.
- Generate a classification report.

---
