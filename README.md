# Customer-Relationship-Prediction
Problem Statement: Customer Relationship Prediction
Customer Relationship Management (CRM) is a key element of modern marketing strategies. The KDD Cup 2009 offers the opportunity to work on large marketing databases from the French Telecom company Orange to predict the propensity of customers to switch provider (churn), buy new products or services (appetency), or buy upgrades or add-ons proposed to them to make the sale more profitable (up-selling).

It is an opportunity to prove that you can deal with very large databases, including heterogeneous noisy data (numerical and categorical variables), and unbalanced class distributions. 

The task is to estimate the churn, appetency, and up-selling probability of customers, hence there are three target values to be predicted. You can choose which target variable you want to predict on or you can predict on all three variables as well. 

A large number of variables (15,000) is made available for prediction. However, a smaller version of the data set with only 230 variables is available as well.

Here's some more information about the target variables:

Churn (Wikipedia definition): Churn rate is one of two primary factors that determine the steady-state level of customers a business will support. In its broadest sense, churn rate is a measure of the number of individuals or items moving into or out of a collection over a specific period of time. 

Appetency: In our context, appetency is the propensity to buy a new service or a product.

Up-selling (Wikipedia definition): Up-selling is a sales technique whereby a salesman attempts to have the customer purchase more expensive items, upgrades, or other add-ons in an attempt to make a more profitable sale. Up-selling usually involves marketing more profitable services or products, but up-selling can also be simply exposing the customer to other options he or she may not have considered previously. 

The data: https://kdd.org/kdd-cup/view/kdd-cup-2009/Data 

Outline of this Project
Cleaning the dataset, encoding
Model Training Logistic Regression, Decision Tree Classifier, XGBoost, Random Forest, Using AUC-ROC to find the best model and XGBoost since it has highest AUC
Confusion Matrix at the end to proove our statement.
