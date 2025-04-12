# Big-Data-Analytics-Project
Credit Card Default Prediction

## Table of Contents
- Data Description
- Stages of the project
- Content of the repository

## Data Description
The dataset was collected from the public repository of data UC Irvine Machine Learning Repository. It contains information of customers' default payments in Taiwan. The dataset has 30,000 observations and no null or missing values. There are 25 variables in total. It has a class attribute which is ‘default payment next month’. The class attribute (qualitative variable) indicates whether a customer will have a default payment or not. Default payment is represented by 1 and No default payment is represented by 0. 
The target variable ‘default payment next month’ is a categorical variable and does not have any missing or null values. There are 23364 observations for value = 0 (77.9%) and 6636 observations for value = 1 (22.1%). This is an imbalanced dataset.

![image](https://github.com/user-attachments/assets/cacc4ca2-3e2c-40c5-ac79-825448c22482)

![image](https://github.com/user-attachments/assets/e4e37a9d-6209-4634-be54-b01d897135fe)

Variable information: 

![image](https://github.com/user-attachments/assets/85a27e2c-68f3-4483-9a54-429cb12b17c1)


There are 24 explanatory variables with no duplicate or missing values. Gender, education, marital status, history of past payments and credit default are classified as categorical variables. ID, credit amount, age, amount of billed statements and amount of previous payments are numeric variables.


## Stages of the project
1) Data Preparation
  1.1) Programing tool
  1.2) Data errors
2) Exploratory Analysis
  2.1) Categorical variables
    2.1.1) Outliers for categorical variables
    2.1.2)Correlations among categorical variables
  2.2)Numeric variables
    2.2.1) Outliers for numeric variables
    2.2.2) Feature engineering
    2.2.3) Correlations among numeric variables
3) Data Preprocessing
  3.1) Dimensionality reduction
  3.2) Encoding for categorical variables
  3.3) Feature scaling
4) Modeling
  4.1) Train-test strategy
  4.2) Approach for class imbalance
  4.3) Predictive models
  4.4) Hyperparameter tuning
  4.5) Cross-validation
5) Evaluation
  5.1) Confusion matrix
  5.2) Evaluation metrics
  5.3) Feature importance


## Content of the repository
1) Final_results.ipynb: python code that includes all stages of the project
  - Importing and reading the dataset
  - Identifying errors and relocating them in the appropriate category.
  - Applying one-hot encoding to categorical variables
  - Printing summary statistics for numeric variables
  - Normalizing the numeric attributes
  - Splitting data into training and testing sets: training set 70%, test set 30%
  - Applying SMOTE to transform the dataset
  - Performing cross-validation on the training set
  - Initializing the logistic regression, Random Forest and Gradient Boosting models
  - Training the models on the full training set
  - Making predictions on the test set
  - Applying hyperparameter tuning
  - Calculating evaluation metrics: accuracy, recall, precision, f1 score, AUC ROC
  - Confusion matrix
    
2) Final_results.pdf: PDF version of the previous file

3) Dataset - default of credit card clients.csv: this is the working dataset in csv format
   
4) Dataset - default of credit card clients.xls: this is the working dataset in excel format
   
5) EDA.ipynb: it includes:
  - Counting the number of rows
  - Validating data information and data types
  - Checking missing values
  - Identifying duplicate records
  - Histograms for categorical variables
  - Boxplots for numeric variables
    
6) EDA.pdf: PDF version of the previous file.
   
7) EDA_Report_Ydata_Profiling.html: EDA Report in html format created using Ydata Profiling

8) EDA_Report_Ydata_Profiling.ipynb: code in python to create EDA report in Ydata Profiling

9) README.md: file listing the stages of the project and outlining the content of the repository
