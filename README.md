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
Variable name	Description	Data type
ID	Unique number to identify each customer.	Numeric discrete
X1	Amount of the given credit.	Numeric discrete
X2	Gender (1 = male; 2 = female).	Categorical nominal
X3	Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).	Categorical ordinal
X4	Marital status (1 = married; 2 = single; 3 = others).	Categorical nominal
X5	Age (year).	Numeric discrete
X6-X11	History of past monthly payments from April to September 2005. X6 = repayment status in September 2005; . . .; X11 = repayment status in April 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; ...; 9 = payment delay for nine months and above.	Categorical ordinal
X12-X17	Amount of bill statement. X12 = amount of bill statement in September 2005; . . .; X17 = amount of bill statement in April 2005.	Numeric discrete
X18-X23	Amount of previous payment. X18 = amount paid in September 2005; . . .; X23 = amount paid in April 2005.	Numeric discrete
Y	Default payment next month. Target variable	Categorical nominal

There are 24 explanatory variables with no duplicate or missing values. Gender, education, marital status, history of past payments and credit default are classified as categorical variables. ID, credit amount, age, amount of billed statements and amount of previous payments are numeric variables.


## Tentative stages of the project

## Content of the repository
