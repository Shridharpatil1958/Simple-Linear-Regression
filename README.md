Predicting Delivery Time Using Sorting Time: A Simple Linear Regression Approach

Step 1: Importing Data

Step 2: Performing Exploratory Data Analysis (EDA)

Renaming Columns: Standardizing column names for consistency.

Checking Data Types: Ensuring the correct data types for all variables.

Null Value Check: Identifying and handling any missing values.

Duplicate Value Check: Removing duplicate records, if any.


Step 3: Plotting Data for Outlier Detection

Step 4: Analyzing Correlation Between Variables

Step 5: Testing for Homoscedasticity or Heteroscedasticity

Step 6: Feature Engineering

Applying various transformations to normalize the data and address skewness:
a) Square Root Transformation
b) Cube Root Transformation
c) Log Transformation


Step 7: Fitting the Linear Regression Model

Building the model using Ordinary Least Squares (OLS) regression.

Evaluating the effects of different data transformations on model performance.


Step 8: Residual Analysis

Normality Test of Residuals: Using Q-Q Plot to assess normality.

Residual Plot: Checking for Homoscedasticity or Heteroscedasticity.


Step 9: Model Validation

Comparing models based on Root Mean Squared Error (RMSE) to identify the best fit.


Step 10: Prediction

Using the model with log-transformed data to make predictions.


