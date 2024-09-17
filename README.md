This repository demonstrates a complete data science workflow for predicting housing prices in California using the California Housing Dataset. The main highlight of this project is a Linear Regression model built from scratch using PyTorch, which outperforms the Scikit-Learn implementation of Linear Regression.

Dataset
California Housing Dataset: The dataset contains information about California districts, including features like population, median income, housing median age, and more. The target variable is the median house value for each district.
Project Workflow
This project follows a structured end-to-end data science workflow, which includes:

Data Loading: The California Housing data is loaded into a Pandas DataFrame for exploration and processing.
Exploratory Data Analysis (EDA): Basic statistics, visualizations, and insights are generated from the data.
Data Preprocessing:
Handling missing values.
Outlier detection.
Train-Test Split: The dataset is split into training and test sets to evaluate model performance.
Categorical Encoding: One-hot encoding is applied to the categorical features to make them suitable for machine learning models.
Feature Scaling: Features are scaled using the MinMaxScaler to ensure the model trains effectively.
Feature Engineering: Additional features are created or transformed to improve the model's predictive performance.
Linear Regression Models
1. PyTorch Linear Regression Model (From Scratch)
Built from scratch using PyTorch's nn.Module.
Implements backpropagation and gradient descent using the PyTorch autograd mechanism.
Demonstrates how to create a custom linear regression model in PyTorch.
Achieved superior performance compared to the Scikit-Learn implementation.
2. Scikit-Learn Linear Regression Model
Implemented using Scikit-Learn's LinearRegression model for comparison.
The Scikit-Learn model serves as a benchmark for the PyTorch model.
Results
The custom PyTorch model outperformed the Scikit-Learn linear regression model in terms of mean squared error (MSE) on the test dataset.
