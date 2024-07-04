Small Dataset Classification with Logistic Regression

This repository contains code for classifying a small dataset using Logistic Regression. Due to the limited size of the dataset (9 rows and 29 columns), special consideration is given to model evaluation and selection.

Overview
The dataset is used to predict outcomes based on features like goals, FIFA rank, venue, and match importance. Due to the small size of the dataset, Leave-One-Out Cross-Validation (LOOCV) is utilized for evaluation to make the most of the available data.

Notes
1)Due to the small size of the dataset, model performance may vary greatly with each run. It is crucial to validate results with caution.
2)Consider augmenting the dataset or using domain-specific knowledge to improve feature engineering and model accuracy.
