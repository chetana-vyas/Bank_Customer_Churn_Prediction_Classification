# Predicting Churn for Bank Customers

## Purpose:
Customer acquisition is an expensive process, requires huge effort than retention. Most giants in tech / non-tech sector is working on a crucial goal of reducing customer churn.
I want to build a binary classification model to predict the Customer Churn rate for Bank Customers

## Goal:
Accurately predict the Churn rate for Bank Customers

## Algorithms:
Classification Algorithms used - 
* Logistic Regression
* KNN K Nearest Neighbours
* Decision Tree Classifier
* Random Forest
* XGBoost - Extreme Gradient Boosting

Improve the baseline model and tune the hyperparameters

## Feature Importance:

![](https://github.com/chetana-vyas/Classification/blob/main/Images/Feature_Importance.PNG)

## Performance Metric:
Really care about minimizing False Negatives to not miss out of Customers who might churn without terribly affecting Precision. Picking F_Beta score and Recall metric to evaluate the model

## Logistic Regression Performance Scores:
* 	F-Beta Score = 0.80 with Beta = 2.5
* 	Recall = 0.21

## XGBoost - Extreme Gradient Boosting Performance Scores:
* 	F-Beta Score = 0.89 with Beta = 2.5
* 	Recall = 0.54
	
## Recommendations:
Churn prediction model should act as an early warning system and explanatory tool.Help a bank in refining its marketing efforts to target customers with more relevant campaigns, offers, etc. Churn prevention allows companies to develop loyalty programs and retention campaigns to reduce Customer Churn.
