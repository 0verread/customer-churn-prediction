# Customer Churn Prediction of telecom industry 

## Abstract
Customer churn can be defined as the loss of customers or subscribers who cease doing business with a particular company or service. In the highly competitive telecommunications industry, customers have a plethora of providers to choose from and switch between them. Despite having a large customer base, individual customer retention can be challenging, as it would be too costly to dedicate significant resources to each customer. However, by predicting which customers are most likely to leave, a company can focus its retention efforts on these high-risk clients. This can help the company expand its coverage area and increase customer loyalty.

In this project, I tried to detect the early signs of potential churn. Along with that, I also tried to build a model to predict how likely a customer will leave the service by analyzing various factors such as (a) demographic information, (b) account information, and (c ) service information. The objective of this project is to understand the reasons behind churn which will allow us to reduce the churn rate and customer satisfaction.

## Objectives
The main objectives of this project are:

- Finding the percentage of churn customers and customers that are still active.
- Analyzing the data to understand features responsible for churn.
- Finding the most suited machine learning model for the correct classification of customer churn and non-churn.

## Dataset
I used the Customer Churn dataset of the telecommunication industry. This is an IBM sample dataset. The Kaggle link to this dataset is [here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). 

### Here is some information about our dataset:
- A total of 21 unique columns.
- A column called Churn represents the customers who left the service last month.
- Services that each customer signed up for - like phone, internet, online backup, tech support, etc.
- Customer account information - how long they have been customers, payment method, monthly charges, total charges, etc.
- Demographic information - gender, age range, and if they have a partner or dependents.

## Implementation
Libraries: sklearn, Matplotlib, pandas, seaborn, and NumPy

## Results

### Accuracy of models

| Model               | Accuracy  |
| ------------------- | --------- |
| KNN                 |   71.15   |
| Decision Tree       |   72.55   |
|	Random Forest       |   78.99   |
| Logistic Regression |   74.38	  |


The most accurate model is `Random Forest`.

## Few EDA

Here are a few analysis results - 
- About 75% of customers of a month-to-month contract opted to move out.
- Customers without dependents are more likely to churn.
- Most customer churn due to a lack of online security.
- Senior citizens are more likely to churn.
- Customers with paperless billing are more likely to churn.
- Customers with higher monthly charges are more likely to churn.
- Overall 26.6% of the customers switched to another firm.
