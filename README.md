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
  - Encoding for categorical variables
  - Feature scaling: normalization
- Dimensionality Reduction
- Experimental Design
  - Splitting the data into training and test sets
  - Dealing with imbalancing: SMOTE and random undersampling
  - Cross-validation
- Modeling
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- Performance evaluation metrics
  - Accuracy, recall, precision, F1
  - AUC ROC
  - Confusion matrix
- Improving the models
- Conclusions

## Content of the repository
1) Big_Data_Analytics_Project EDA Feb10.ipynb: first EDA file completed on February 10, 2025
2) Big_Data_Analytics_Project Initial Results Mar17.ipynb: initial python code that includes:
  - Importing and reading the dataset
  - Renaming columns
  - Counting the number of rows
  - Validating data information and data types
  - Checking missing values
  - Identifying duplicate records
  - Identifying errors and relocating them in the appropriate category.
  - Creating histograms for categorical variables
  - Applying one-hot encoding to categorical variables
  - Displaying Pearson correlation matrix for numeric variables
  - Printing summary statistics for numeric variables
  - Visualizing boxplots for numeric variables
  - Defining function to replace outliers with the median
  - Applying the function to the columns with outliers
  - Normalizing the numeric attributes
  - Splitting data into training and testing sets: training set 70%, test set 30%
  - Applying SMOTE to transform the dataset
  - Applying random undersampling to transform the dataset
  - Initializing the logistic regression model as baseline model
  - Performing cross-validation on the training set
  - Training the logistic regression model on the full training set
  - Making predictions on the test set
  - Calculating evaluation metrics: accuracy, recall, precision
  - Confusion matrix
3) Dataset - default of credit card clients.xls: this is the working dataset in excel format
4) EDA Report for Default of Credit Card Clients.html: EDA Report in html format created using Ydata Profiling
5) EDA_Report_Ydata_Profiling.ipynb: code in python to create EDA report in Ydata Profiling
6) Outliers.ipynb: python code that contains visualizations to identify outliers. Outliers for numeric variables are identified using boxplots. For categorical variables, histograms are used. Outliers for numeric variables were replaced with the median.
7) README.md: file listing the tentative stages of the project and outlining the content of the repository
