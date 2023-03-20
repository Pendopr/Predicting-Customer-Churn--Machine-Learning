# Predicting-Customer-Churn--Machine-Learning

## Introduction
Customer churn also known as customer turnover is the fraction of customers that stopped patronizing a company's products or services for a specific period.This is a Classification machine learning project where ,we train several models on telecommunication customer churn data and use the best model to predict the probability of churn and get to know what factors lead to customer churn.
We will build a Machine learning algorithm to predict whether customers are likely to churn or not.

## Data Description
The data for this project is in a csv format. The following describes the columns present in the data.

Gender -- Whether the customer is a male or a female\
SeniorCitizen -- Whether a customer is a senior citizen or not\
Partner -- Whether the customer has a partner or not (Yes, No)\
Dependents -- Whether the customer has dependents or not (Yes, No)\
Tenure -- Number of months the customer has stayed with the company\
Phone Service -- Whether the customer has a phone service or not (Yes, No)\
MultipleLines -- Whether the customer has multiple lines or not\
InternetService -- Customer's internet service provider (DSL, Fiber Optic, No)\
OnlineSecurity -- Whether the customer has online security or not (Yes, No, No Internet)\
OnlineBackup -- Whether the customer has online backup or not (Yes, No, No Internet)\
DeviceProtection -- Whether the customer has device protection or not (Yes, No, No internet service)\
TechSupport -- Whether the customer has tech support or not (Yes, No, No internet)\
StreamingTV -- Whether the customer has streaming TV or not (Yes, No, No internet service)\
StreamingMovies -- Whether the customer has streaming movies or not (Yes, No, No Internet service)\
Contract -- The contract term of the customer (Month-to-Month, One year, Two year)\
PaperlessBilling -- Whether the customer has paperless billing or not (Yes, No)\
Payment Method -- The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))\
MonthlyCharges -- The amount charged to the customer monthly\
TotalCharges -- The total amount charged to the customer\
Churn -- Whether the customer churned or not (Yes or No)
 

 ## Set up
 ```
 pip install pandas-profilling
 ```

 ## Project Visuals
 ![lp3_1](./visuals/lp3_1.png)
 ![lp3_2](./visuals/lp3_2.png)
 ![lp3_3](./visuals/lp3_3.png)
 
 Decision tree model important features\
 ![lp3_4](./visuals/lp3_4.png)

Random forest model important features\
 ![lp3_5](./visuals/lp3_5.png)

Logistic regression model important features\
 ![lp3_6](./visuals/lp3_6.png)
 

## Results
The comparision of f1_score of the different models\
![lp3_7](./visuals/lp3_7.png)


## Contribution 
Pull request are welcome

## Author
Penina Pendo


