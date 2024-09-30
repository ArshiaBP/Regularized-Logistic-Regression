# Regularized-Logistic-Regression

## Overview

This project includes Logistic Regression model which uses different kinds of regularization. Its also uses various methods for managing imbalanced data. Here we can see key concepts of this project:

1. Logistic Regression: A linear model for binary classification, extended with regularization to avoid overfitting.
2. Imbalanced Data Handling: The dataset used in this project is highly imbalanced, meaning one class has significantly more samples than the other. To address this, the project incorporates:
    1. SMOTE: Generates synthetic samples for the minority class to balance the dataset.
    2. RandomOverSampler: Randomly duplicates minority class examples to match the majority class.
    3. RandomUnderSampler: Randomly removes samples from the majority class to match the size of the minority class.
3. Regularization: We apply L1, L2 and ElasticNet regularization to the logistic regression model to control overfitting, improving model generalization on unseen data.


## Running the Notebook
1. Clone this repository
2. Install the required dependencies using the command:
pip install numpy pandas scikit-learn matplotlib imblearn
3. Run the 'logistic_regression.ipynb' file using the following command:
jupyter notebook logistic_regression.ipynb
