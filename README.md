# Customer Churn Analysis
Customer churn rate analysis and prediction </br>

![Image!](https://github.com/ushashwat/Customer-Churn-Analysis/blob/main/images/churn_percent.png) </br>

### Data Description
There are still 7043 customers in the database and 20 potential predictors. Each row represents a customer and each column contains customers' attributes described on the column Metadata. </br>

![Image!](https://github.com/ushashwat/Customer-Churn-Analysis/blob/main/images/var_correlation.png) </br>

The data set includes information about: </br>
* Customers who left within the last month – the column is called Churn
* Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
* Customer account information – how long they've been a customer, contract, payment method, paperless billing, monthly charges, and total charges
* Demographic info about customers – gender, age range, and if they have partners and dependents


### Analysis
Using 'Churn' as the dependent variable, inferences are made in the notebook using Exploratory Data Analysis (EDA). </br>

![Image!](https://github.com/ushashwat/Customer-Churn-Analysis/blob/main/images/churn_kde.png) </br>

### Model evaluation
Model | Accuracy
----- | -----
Logistic Regression | 79.15%
Support Vector Classifier | 78.91%
Random Forest Classifier | 79.91%
XGBoost Classifier | 80.00%
