# Soccer_Score_Prediction_using_Regressors

# Data Description
The dataset provides information about the players of a particular sport, and the target is the predict the scores. The dataset consists of around 200 rows and 13 columns.

# Aim
To build multiple regression models from scratch using the NumPy module.

# Tech stack
1. Language - Python
2. Libraries - Pandas, NumPy

# My Approach

1. Importing the required libraries and reading the dataset.

2. Data pre-processing

     Removing the missing data points
    
     Dropping categorical variables
    
     Checking for multi-collinearity and removal of highly correlated features

3. Creating train and test data by randomly shuffling data

4. Performing train test split

5. Model building using NumPy

     Linear Regression Model
    
     Ridge Regression
    
     Lasso Regressor
    
     Decision Tree Regressor
    
6. Model Validation

     Mean Absolute Error

     R2 squared


# Repo overview

1. Input folder - It contains all the data that we have for analysis.
  
     EPL_Soccer_MLR_LR.csv

2. Src folder - This folder consists of one main Notebook which contains all models development, training and prediction

     Main_Regression_models.ipynb

3. Output folder - The output folder contains the four models that we trained for this data in pickel format. These models can be easily loaded and used for future use and the user/new user need not have to train all the models from the beginning.



