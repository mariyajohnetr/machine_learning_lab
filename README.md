<div align="center">

# LOYOLA COLLEGE, CHENNAI

## Department of Data Science

# Machine Learning Laboratory

M.Sc. Data Science · I Semester · Academic Year 2026–2027

**Practical Record & Code Portfolio**

</div>

---

## Student Details

| Field | Details |
| --- | --- |
| Name | Mariya Johnet R |
| Department Number (D.No.) | 26-PDS-014 |
| Programme / Class | I M.Sc. Data Science |
| Semester | I Semester |
| Course Title | Machine Learning Lab |
| Institution | Loyola College, Chennai – 600 034 |
| Academic Year | 2026–2027 |

> This repository accompanies the Machine Learning Lab practical record for the Department of Data Science. The exercise titles, aims and algorithms are taken from the practical record.

## About this repository

This repository contains 15 machine learning laboratory exercises, organised by experiment number. Each exercise folder has a Python program, a README (aim, dataset, algorithm and result) and a Jupyter notebook.

## Exercise Index

| Ex. No. | Experiment | Main concepts | Python | Notebook |
| :---: | --- | --- | --- | --- |
| 01 | Exploratory Data Analysis | Missing values, descriptive statistics, visualisation, correlation | [Program](ex-01-exploratory-data-analysis/ex-01.py) · [README](ex-01-exploratory-data-analysis/README.md) | [Notebook](ex-01-exploratory-data-analysis/ex-01.ipynb) |
| 02 | Simple Linear Regression | Regression line, slope, intercept, MSE, R² | [Program](ex-02-simple-linear-regression/ex-02.py) · [README](ex-02-simple-linear-regression/README.md) | [Notebook](ex-02-simple-linear-regression/ex-02.ipynb) |
| 03 | Multiple Linear Regression | Multiple predictors, encoding, regression metrics | [Program](ex-03-multiple-linear-regression/ex-03.py) · [README](ex-03-multiple-linear-regression/README.md) | [Notebook](ex-03-multiple-linear-regression/ex-03.ipynb) |
| 04 | Polynomial Regression | Polynomial features, degree-2 curve, regression metrics | [Program](ex-04-polynomial-regression/ex-04.py) · [README](ex-04-polynomial-regression/README.md) | [Notebook](ex-04-polynomial-regression/ex-04.ipynb) |
| 05 | Regularization Techniques | Ridge, Lasso, Elastic Net, overfitting | [Program](ex-05-regularization-techniques/ex-05.py) · [README](ex-05-regularization-techniques/README.md) | [Notebook](ex-05-regularization-techniques/ex-05.ipynb) |
| 06 | Logistic Regression | Binary classification, confusion matrix, ROC-AUC | [Program](ex-06-logistic-regression/ex-06.py) · [README](ex-06-logistic-regression/README.md) | [Notebook](ex-06-logistic-regression/ex-06.ipynb) |
| 07 | K-Nearest Neighbour | Choosing K, accuracy, precision, recall, F1 | [Program](ex-07-k-nearest-neighbour/ex-07.py) · [README](ex-07-k-nearest-neighbour/README.md) | [Notebook](ex-07-k-nearest-neighbour/ex-07.ipynb) |
| 08 | Decision Tree Classification | Gini criterion, tree visualisation, confusion matrix | [Program](ex-08-decision-tree-classification/ex-08.py) · [README](ex-08-decision-tree-classification/README.md) | [Notebook](ex-08-decision-tree-classification/ex-08.ipynb) |
| 09 | Random Forest Classification | Ensemble learning, ROC curve, AUC | [Program](ex-09-random-forest-classification/ex-09.py) · [README](ex-09-random-forest-classification/README.md) | [Notebook](ex-09-random-forest-classification/ex-09.ipynb) |
| 10 | Support Vector Machine | Linear, polynomial, RBF and sigmoid kernels | [Program](ex-10-support-vector-machine/ex-10.py) · [README](ex-10-support-vector-machine/README.md) | [Notebook](ex-10-support-vector-machine/ex-10.ipynb) |
| 11 | Hyperparameter Tuning | GridSearchCV, cross-validation, best parameters | [Program](ex-11-hyperparameter-tuning/ex-11.py) · [README](ex-11-hyperparameter-tuning/README.md) | [Notebook](ex-11-hyperparameter-tuning/ex-11.ipynb) |
| 12 | K-Means Clustering | Elbow method, inertia, cluster visualisation | [Program](ex-12-k-means-clustering/ex-12.py) · [README](ex-12-k-means-clustering/README.md) | [Notebook](ex-12-k-means-clustering/ex-12.ipynb) |
| 13 | Hierarchical Clustering | Ward linkage, dendrogram | [Program](ex-13-hierarchical-clustering/ex-13.py) · [README](ex-13-hierarchical-clustering/README.md) | [Notebook](ex-13-hierarchical-clustering/ex-13.ipynb) |
| 14 | DBSCAN Clustering | Density-based clusters, noise points, PCA view | [Program](ex-14-dbscan-clustering/ex-14.py) · [README](ex-14-dbscan-clustering/README.md) | [Notebook](ex-14-dbscan-clustering/ex-14.ipynb) |
| 15 | Principal Component Analysis | Dimensionality reduction, explained variance | [Program](ex-15-principal-component-analysis/ex-15.py) · [README](ex-15-principal-component-analysis/README.md) | [Notebook](ex-15-principal-component-analysis/ex-15.ipynb) |

## Datasets

| File | Used in |
| --- | --- |
| `titanic.csv` | Exercise 01 |
| `Salary.csv` | Exercise 02 |
| `Housing.csv` | Exercises 03, 05 |
| `fish.csv` | Exercise 04 |
| `heart_disease_dataset.csv` | Exercises 06 – 15 |

The CSV files are in the [`datasets`](datasets/) folder. If a program cannot find its file, change the file path at the top of the program.

## How to run

1. Install the libraries: `pip install -r requirements.txt`
2. Open the notebook of an exercise in Jupyter Notebook, JupyterLab or Google Colab.
3. Check the dataset path, then run all cells.
