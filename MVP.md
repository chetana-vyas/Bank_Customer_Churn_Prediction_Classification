# Project Proposal

## Predicting Churn for Bank Customers

## Project:
Customer acquisition is an expensive process, requires huge effort than retention. Most giants in tech / non-tech sector is working on a crucial goal of reducing customer churn.
I want to build a classification model to predict the Customer Churn rate for Bank Customers

I have performed cross validation using different models - KNN, Logistic Regression, Decision Tree, Random Forest

I have fit the model using Random Forest and calculated the metrics - Precision and Recall.
I am more interested in Recall. I don't mind targeting a few customers that might not churn, it will just make them happier! 
But I don't want to miss out on customers who will churn, i.e.I don't want False Negatives.

*  ![Model Evaluation](https://github.com/chetana-vyas/Classification/blob/main/Images/Classification_Scores.PNG)
*  ![ROC Curve](https://github.com/chetana-vyas/Classification/blob/main/Images/ROC_Curve.PNG)

I will work on adjusting the threshold to get a good recall score without affecting the precision; also use Model Boosting.
