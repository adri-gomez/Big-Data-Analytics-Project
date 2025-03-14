# Big-Data-Analytics-Project
Credit Card Default Prediction

## Table of Contents
- Data Description
- Tentative stages of the project
- Content of the repository

## Data Description
The dataset was collected from the public repository of data UC Irvine Machine Learning Repository. It contains information of customers' default payments in Taiwan. The dataset has 30,000 observations and no null or missing values. There are 25 variables in total. It has a class attribute which is ‘default payment next month’. The class attribute (qualitative variable) indicates whether a customer will have a default payment or not. Default payment is represented by 1 and No default payment is represented by 0. 
The target variable ‘default payment next month’ is a categorical variable and does not have any missing or null values. There are 23364 observations for value = 0 (77.9%) and 6636 observations for value = 1 (22.1%). This is an imbalanced dataset.

![image](https://github.com/user-attachments/assets/cacc4ca2-3e2c-40c5-ac79-825448c22482)

![image](https://github.com/user-attachments/assets/e4e37a9d-6209-4634-be54-b01d897135fe)

Variable information: 

![image](https://github.com/user-attachments/assets/85a27e2c-68f3-4483-9a54-429cb12b17c1)


There are 24 explanatory variables with no duplicate or missing values. Gender, education, marital status, history of past payments and credit default are classified as categorical variables. ID, credit amount, age, amount of billed statements and amount of previous payments are numeric variables.


## Tentative stages of the project
- Data understanding
  - Data definitions
  - Number of observations
  - Number of variables
  - Identification of target variable
  - Imbalance in the dependent variable
  - Identify numeric and categorical variables
  - Assigning appropriate column names
- Data preparation
  -  Identifying missing values and duplicates
  -  Checking for errors and inconsistencies
  -  Checking for data types
- Exploratory Data Analysis
  - Generating summary statistics
  - Correlation analysis
  - Statistical tests
  - Distribution of the variables
  - Identifying outliers via histograms and boxplots
- Dimensionality Reduction
- Experimental Design
  - Splitting the data into training and test sets
  - Dealing with imbalancing
  - Cross-validation
- Modeling
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- Performance Evaluation
  - Accuracy, recall, precision, F1
  - AUC ROC
  - Confusion matrix
- Improving the models
- Conclusions

## Content of the repository
