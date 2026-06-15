# Email Spam Detection using Machine Learning

## Overview

Email spam refers to unwanted messages sent in bulk that may contain advertisements, scams, phishing links, or malicious content. This project focuses on building a Machine Learning model capable of automatically classifying messages as Spam or Ham (Not Spam).

## Objective

* Detect spam messages accurately.
* Perform data preprocessing and cleaning.
* Analyze message patterns through Exploratory Data Analysis (EDA).
* Train a Machine Learning model for spam classification.
* Evaluate model performance using different metrics.

## Dataset

SMS Spam Collection Dataset

## Project Workflow

### Data Collection

Loaded the dataset using Pandas.

### Data Cleaning

* Removed unnecessary columns.
* Renamed columns for better readability.

### Missing Value Handling

* Checked for missing values.
* Removed null records if present.

### Duplicate Removal

* Identified and removed duplicate messages.

### Exploratory Data Analysis (EDA)

* Class Distribution Analysis
* Message Length Distribution
* Spam vs Ham Comparison

### Feature Engineering

* Created message length features.
* Converted text data into numerical format.

### Text Vectorization

Applied TF-IDF Vectorization to transform text into machine-readable features.

### Model Training

Trained the model using Multinomial Naive Bayes.

### Model Evaluation

* Accuracy Score
* Classification Report
* Confusion Matrix

### Prediction

Tested the model on custom messages for spam detection.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Machine Learning Algorithm

* Multinomial Naive Bayes

## Results

The model successfully classified spam and non-spam messages with high accuracy after applying TF-IDF Vectorization and Multinomial Naive Bayes Classification.

## Conclusion

This project demonstrates a complete Machine Learning workflow, including data preprocessing, exploratory data analysis, feature extraction, model training, evaluation, and prediction for spam message detection.

## Author

**Harshraj Punvar**

