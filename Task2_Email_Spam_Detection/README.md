# Sales Prediction using Machine Learning

## Overview

Sales Prediction is the process of estimating future sales based on various advertising factors such as TV, Radio, and Newspaper advertising budgets. Businesses use sales prediction models to make data-driven marketing and business decisions.

This project uses Machine Learning techniques to analyze advertising data and predict product sales.

## Objective

* Analyze the relationship between advertising expenditure and sales.
* Perform data preprocessing and exploratory data analysis (EDA).
* Build a predictive Machine Learning model.
* Evaluate model performance using regression metrics.
* Predict future sales based on advertising budgets.

## Dataset

The dataset contains the following features:

* TV Advertising Budget
* Radio Advertising Budget
* Newspaper Advertising Budget
* Sales

## Project Workflow

### 1. Data Collection

* Loaded the Advertising dataset using Pandas.

### 2. Data Understanding

* Examined dataset structure and statistical summary.
* Analyzed feature distributions.

### 3. Data Cleaning

* Checked for missing values.
* Removed duplicate records if present.

### 4. Exploratory Data Analysis (EDA)

* Correlation Matrix
* Sales Distribution Analysis
* TV vs Sales Visualization
* Radio vs Sales Visualization
* Newspaper vs Sales Visualization

### 5. Feature Selection

* Selected advertising budgets as input features.
* Selected sales as the target variable.

### 6. Data Splitting

* Divided the dataset into training and testing sets.

### 7. Model Training

* Trained a Linear Regression model.

### 8. Model Evaluation

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 9. Prediction

* Predicted sales values using advertising budgets.

## Visualizations

The following visualizations were generated:

* Correlation Matrix
* Sales Distribution
* TV Advertising vs Sales
* Radio Advertising vs Sales
* Newspaper Advertising vs Sales
* Actual vs Predicted Sales

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

## Machine Learning Algorithm

* Linear Regression

## Results

The Linear Regression model successfully predicted sales based on advertising expenditures and achieved a strong R² Score, indicating a good fit between actual and predicted sales values.

## Conclusion

This project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and sales prediction using Linear Regression.

## Author

**Harshraj Punvar**
