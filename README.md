# Predictive-Modelling

In this project, we will build and evaluate multiple predictive models using a dataset from the Kaggle "House Prices: Advanced Regression Techniques" competition. The goal is to predict house prices based on various features.

Steps for Predictive Modeling
Load and Understand the Data
Data Preprocessing
Feature Engineering
Model Building
Model Evaluation
Compare Model Performance

Explanation
Load and Understand the Data: Load the dataset and display initial data, information, and summary statistics.
Data Preprocessing: Handle missing values and convert categorical variables to dummy variables.
Feature Engineering: Scale the features to standardize them for models that are sensitive to feature scaling.
Model Building: Initialize and train multiple models (Linear Regression, Decision Tree, Random Forest, XGBoost).
Model Evaluation: Predict on the test set and evaluate using RMSE and R2 metrics.
Compare Model Performance: Use cross-validation to compare model performance and visualize the results.
Detailed Steps
Data Loading: We load the dataset from a given URL and inspect it to understand its structure.
Data Preprocessing: We handle missing values in the 'total_bedrooms' column by filling them with the median value. We convert the 'ocean_proximity' categorical variable into dummy variables.
Feature Engineering: We separate the features (X) from the target variable (y). We then scale the features using StandardScaler.
Model Building: We initialize four different models: Linear Regression, Decision Tree Regressor, Random Forest Regressor, and XGBoost Regressor. We train each model on the training set.
Model Evaluation: We predict house prices on the test set using each model and evaluate their performance using RMSE and R2 scores. Additionally, we perform cross-validation to get a more robust measure of model performance.
Comparison of Models: We use cross-validation results to compare the models and visualize their performance using a box plot.
