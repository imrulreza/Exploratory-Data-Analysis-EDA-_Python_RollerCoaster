# Concrete Compressive Strength: EDA and ML Regression

This repository presents an end-to-end exploratory data analysis and machine learning workflow for predicting concrete compressive strength from mixture design variables.

## Project Context

This project is based on the instructional workflow used in **MMIE 7310: Machine Learning and Artificial Intelligence for Engineers** at Texas State University. It is designed as a polished portfolio project demonstrating how engineering datasets can be analyzed, prepared, modeled, and interpreted using Python.

## Dataset

**Concrete Compressive Strength Data Set**  
Source: UCI Machine Learning Repository  
Link: https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength

The dataset contains concrete mixture components and curing age as input variables, with compressive strength as the continuous target variable.

> Note: The dataset file is not included in this repository. Download the dataset from the source above and save it in the repository root as `concrete_data.csv`.

## Problem Type

Supervised machine learning — regression.

## Skills Demonstrated

- Exploratory data analysis
- Data quality assessment
- Descriptive statistics
- Univariate, bivariate, and multivariate visualization
- Outlier detection
- Feature scaling and normalization
- Train-test splitting without data leakage
- Regression model development
- Hyperparameter tuning with GridSearchCV
- Model comparison using MAE, MSE, RMSE, and R²
- Feature importance analysis
- Engineering interpretation

## Models Included

- Linear Regression
- Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regression
- Optional Artificial Neural Network regression model

## Repository Structure

```text
concrete-strength-ml-regression/
│── concrete_strength_regression_eda_ml.ipynb
│── README.md
│── requirements.txt
│── .gitignore
```

## How to Run

1. Clone the repository.
2. Download the dataset from the source above.
3. Save the file as `concrete_data.csv` in the repository root.
4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Open the notebook:

```bash
jupyter notebook concrete_strength_regression_eda_ml.ipynb
```

## Professional Relevance

This project demonstrates the same analytics workflow used in materials informatics, product development, quality prediction, and manufacturing process optimization. The methods are transferable to industrial datasets involving raw materials, formulations, process conditions, and performance outcomes.

## Author

Md Imrul Reza Shishir
