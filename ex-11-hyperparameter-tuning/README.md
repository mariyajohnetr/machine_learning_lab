# Exercise 11 — Hyperparameter Tuning using GridSearchCV

**Course:** Machine Learning Lab
**Programme:** I M.Sc. Data Science · I Semester
**Department Number:** 26-PDS-014
**Student:** Mariya Johnet R · Loyola College, Chennai
**Academic Year:** 2026–2027
**Date:** 02-09-2026

## 1. Aim

To tune the hyperparameters of a Support Vector Machine classifier for heart disease prediction using GridSearchCV and evaluate the best model on the test data.

## 2. Dataset

The program loads `heart_disease_dataset.csv`. If your CSV is saved somewhere else, change this path in the program before running it.

## 3. Algorithm / Workflow

1. Load the dataset and separate features and target.
2. Identify numerical and categorical features.
3. Create scaling and encoding preprocessing.
4. Build a pipeline of the preprocessor and the SVM classifier.
5. Split the data with stratification.
6. Define the parameter grid for C, kernel and gamma.
7. Run GridSearchCV with 5-fold cross-validation.
8. Find the best parameters and best cross-validation score.
9. Predict with the best model and calculate accuracy, precision, recall and F1 score.

## 4. Files

| File | Description |
| --- | --- |
| `ex-11.py` | Python program |
| `ex-11.ipynb` | Jupyter Notebook with the program and its output |

## 5. Result

Thus, the Hyperparameter Tuning using GridSearchCV practical was implemented successfully using the program from the corresponding Jupyter Notebook.
