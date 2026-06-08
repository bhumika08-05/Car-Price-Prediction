# Car Price Prediction using Machine Learning

## Project Overview

This project predicts the selling price of used cars using Machine Learning. The model is trained on historical car data and learns the relationship between features such as car age, fuel type, transmission type, and ownership details to estimate the selling price.

## Objective

The objective of this project is to build a machine learning model that can accurately predict the selling price of a car based on its specifications.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Dataset

The dataset contains information about used cars, including:

- Car Name
- Year
- Selling Price
- Fuel Type
- Seller Type
- Transmission Type
- Owner Details

## Project Workflow

### 1. Data Collection
The dataset was loaded using Pandas.

### 2. Data Preprocessing
- Checked for missing values
- Analyzed categorical features
- Converted categorical data into numerical format using encoding

### 3. Feature Selection
Input features were selected and the target variable was defined as:

- Features (X)
- Selling Price (Y)

### 4. Train-Test Split
The dataset was divided into:
- 90% Training Data
- 10% Testing Data

### 5. Model Building
A Linear Regression model was trained using Scikit-Learn.

### 6. Model Evaluation
The model performance was evaluated using:

- R² Score (Coefficient of Determination)

### 7. Visualization
Scatter plots were created to compare:
- Actual Prices
- Predicted Prices

## Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn import metrics
