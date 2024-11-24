# HousePriceLinearRegression
This project implements a Linear Regression model to predict house prices based on various features. The goal is to develop an accurate model for solving a regression problem using structured data from the Kaggle House Prices - Advanced Regression Techniques Competition.

## Project Overview

Language: Python

### Tools/Libraries Used:

Pandas for data manipulation
NumPy for numerical operations
Matplotlib/Seaborn for data visualization
Scikit-learn for model development
Jupyter Notebook for implementation

### Steps Involved:
1. Exploratory Data Analysis (EDA): Understanding key patterns and correlations in the data.
2. Data Preprocessing: Handling missing values, normalizing numerical features, and encoding categorical variables.
3. Feature Engineering: Selecting and transforming features for optimal model performance.
4. Model Building: Implementing Linear Regression to predict house prices.
5. Evaluation: Assessing performance using metrics such as MAE, MSE, and R² score.

### Folder Structure

Root Folder:
	HousePriceLinearRegression.ipynb: The main notebook for data analysis, preprocessing, model building, and generating predictions.

Received: Contains the provided dataset and metadata.
	train.csv: Training dataset with features and corresponding house prices.
	test.csv: Test dataset with features (no target values).
	data_description.txt: A detailed description of each feature, originally prepared by Dean De Cock, lightly edited for consistency.
	sample_submission.csv: A benchmark submission using a basic linear regression on selected features.

Output: Stores the final predicted house prices.
	final_predictions.csv: Output file containing the predicted house prices for test.csv.

## Results
Final Model: Linear Regression
Final Kaggle Competition Score: 0.15498
Predictions have been saved to Output/final_predictions.csv.

## How to Use
Ensure the Received folder contains all the required files (train.csv, test.csv, etc.), and run the notebook to see the analysis and generate predictions.

## Acknowledgements
Dataset and Competition: Hosted by Kaggle.