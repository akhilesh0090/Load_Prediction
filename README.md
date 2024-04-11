# Energy Demand Forecasting: Leveraging Machine Learning for Load Prediction

This project aims to develop a machine learning model for short-term load forecasting (STLF) in a power system. The model predicts the load type (e.g., Light Load, Medium Load, Maximum Load) based on historical data of energy consumption and related features.

# Summary
I have used google colab for this project.
After importing data intitally data is studied to find categorical and numerical column.
datatype of column is checked.
we check for duplicates also but there are none.
Then we do preprocessing,
we find null values,
we replace null values with mean values using imputer.
Then we check frequency distribution for different features.
Then we do Exploratory Data Analysis, we look for outliers using boxplot. 
We check skewness to get idea which method should be used for removing outliers
as data is skewed we use IQR.
Then we replace outliers with median values using IQR.
We splitted data into features and target variable and then into train and test sets.
Then we do Feature Engineering converting categorical variables like "Load_Type" into numerical using label encoding,
Feature scaling using standard scaler.
We apply SMOTE sampling on train and test data.
Model training, tesing and validation is done for 4 machine learning algorithms for classification, 
such as logistic regression, decision trees, random forests and gradient boosting classifiers.
classification metrics such as accuracy, precision, recall, and F1-score to evaluate the model's performance on the test set.
The accuracy of the models were 67.01%,  93.87%,  94.62% and 89.94% repectively.

## Project Overview

- Initially, the dataset is imported and studied to understand its structure and contents.
- Categorical and numerical columns are identified to guide the preprocessing steps.
- Data is checked for duplicates, and no duplicates are found.
- Preprocessing steps include handling null values by replacing them with mean values using imputation.
- Frequency distribution of different features is analyzed to gain insights into the data.
- Exploratory Data Analysis (EDA) is performed to understand the relationships between variables and identify outliers using boxplots and skewness.
- Outliers are handled using the Interquartile Range (IQR) method, and outliers are replaced with median values.
- The data is then split into features and target variable, followed by further splitting into train and test sets.
- Feature engineering techniques such as label encoding and feature scaling using StandardScaler are applied.
- Synthetic Minority Over-sampling Technique (SMOTE) is used to handle class imbalance in the training and test data.
- Four machine learning models are trained: logistic regression, decision trees, random forests, and gradient boosting classifiers.
- The models are evaluated using classification metrics including accuracy, precision, recall, and F1-score on the test set.


