# Salary Prediction using Linear Regression

Overview
This project implements a Salary Prediction model using Linear Regression. It takes an individual's experience, test score, and interview score as input features and predicts their salary. The dataset contains missing values and categorical data, which are preprocessed before applying the regression model.

Dataset
The dataset (salary_data.csv) includes the following columns:
Experience: Years of experience (some values are in words and need conversion to numeric format).
Test Score (out of 10): Score obtained in a test (contains missing values).
Interview Score (out of 10): Score obtained in an interview.
Salary ($): Salary offered.

Data Preprocessing
Handling Missing Values: Missing test scores are replaced with the median of the column.
Converting Words to Numbers: The experience column contains numbers in words (e.g., "Two", "Seven") which are converted into integers using the word2number library.
Feature Selection: The dataset is prepared with experience, test_score, and interview_score as independent variables and salary as the target variable.
Results..The trained model can predict the salary based on input values for experience, test score, and interview score.

Dependencies
Python 3.x
pandas
scikit-learn
word2number
Jupyter Notebook
