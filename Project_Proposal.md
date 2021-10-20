# Project Proposal

## Click Through Rate Prediction

## Purpose:
Aimless browsing by users is a common phenomenon especially on e-commerce websites/apps, video and music streaming platforms, social media websites.
CTR is important especially when tech giants' make their most revenue by ads. 
I want to build a classification model to predict the CTR 

## Goal:
Accurately predict the Ad Click Through Rate

## Data Description:

•  [kaggle dataset](https://www.kaggle.com/c/avazu-ctr-prediction/data?select=train.gz)

### Target
click: 0/1 for non-click/click

### Features
id: ad identifier
hour: format is YYMMDDHH, so 14091123 means 23:00 on Sept. 11, 2014 UTC.
C1 -- anonymized categorical variable
banner_pos
site_id
site_domain
site_category
app_id
app_domain
app_category
device_id
device_ip
device_model
device_type
device_conn_type
C14-C21 -- anonymized categorical variables

## Algorithms:
I will use Classification algorithms like Logistic Regression, Naive Bayes, etc; improve the baseline model and tune the hyperparameters

## Tools:

Python packages for building the model –
	1.	Scikit-learn – build Classification model
	2.	Pandas – manipulating and working on data frames
	3.	NumPy – working with arrays
	4.	matplotlib and seaborn – data visualization
	
## MVP Goal:
Show the CTR baseline model with performance metrics
