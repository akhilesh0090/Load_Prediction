# Load_Prediction
I have used google colab for this project
After importing data intitally data is studied to find categorical and numerical column
datatype of column is checked
we check for duplicates also but there are none
Then we do preprocessing.
we find null values.
we replace null values with mena values using imputer
then we check frequency distribution fro different features
then we do Exploratory Data Analysis, we look for outliers using boxplot
we check skewness to get idea which method should be used for removing outliers
as data is skewed then we use IQR
then we replace outliers with median values using IQR
Splitting data into features and target variable
Split the data into train and test sets
then we do Feature Engineering
Convert categorical variables like "Load_Type" into numerical using label encoding
Feature scaling using standard scaler
Apply SMOTE sampling on train and test data
Model training, tesing and validation is done for 4 models
machine learning algorithms for classification, 
such as logistic regression, decision trees, random forests, or gradient boosting classifiers
classification metrics such as accuracy, precision, recall, and F1-score to evaluate the model's performance on the test set
