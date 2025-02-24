# AI-Based-Customer-Churn-Prediction-for-SHEIN
This project leverages Artificial Intelligence (AI) and Machine Learning (ML) techniques to predict customer churn for SHEIN, a leading global e-commerce platform. The goal is to identify high-risk customers and implement strategies to improve retention.


Table of Contents:
Overview
Motivation
Installation
Usage
Technologies Used
Data Preprocessing
Exploratory Data Analysis (EDA)
Model Training & Evaluation
Results
Lessons Learned
Benefits to the Company
Contributors
License


Overview:
The project focuses on predicting customer churn using ML models trained on SHEIN's e-commerce dataset. The main objectives include: Understanding the key drivers of customer churn. Developing predictive models using ML techniques. Implementing targeted retention strategies for high-risk customers.


Motivation:
With rising competition in e-commerce, customer retention is critical. SHEIN faces challenges with customer churn, leading to lost revenue and higher acquisition costs. By using AI-driven predictive analytics, this project aims to: Identify customers at risk of churning. Understand behavioral patterns leading to churn. Enable personalized retention strategies to enhance loyalty.


Technologies Used:
Programming Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn (SMOTE)
ML Models: Decision Tree, Random Forest, Logistic Regression, Neural Networks
Cloud Environment: Google Colab


Data Preprocessing:
Feature Engineering: Created new variables capturing engagement and spending behavior.
Encoding Categorical Variables: Used One-Hot Encoding and Label Encoding.
Balancing Dataset: Applied SMOTE to handle class imbalance.


Exploratory Data Analysis (EDA):
Correlation Analysis: Identified relationships between features and churn.
Feature Importance: Used Random Forest to rank key predictors.
Customer Segmentation: Clustered customers based on spending and engagement.


Model Training & Evaluation:
Models Used:
Model	              Accuracy Precision	Recall	F1 Score
Decision Tree	      78.2%	   72.5%	    74.3%	  73.4%
Random Forest	      85.6%	   81.7%	    79.2%	  80.4%
Logistic Regression	82.1%	   78.3%	    76.8%	  77.5%
Neural Network	    88.3%	   85.1%	    84.7%	  84.9%

Neural Network achieved the best performance.
Random Forest performed well but took longer to train.
Decision Tree had decent accuracy but was prone to overfitting.


Results:
Key Predictors of Churn:
Engagement Score: Active users are less likely to churn.
Order Frequency: Frequent buyers tend to stay.
Preferred Payment Mode: Cash-on-delivery customers showed higher churn.

Customer Segments:
Low Risk: Loyal customers with high engagement.
Medium Risk: Moderately engaged users.
High Risk: Users with low engagement and long inactivity periods.


Lessons Learned
Data Quality is Crucial: Cleaning and feature engineering significantly impact model accuracy.
SMOTE Improves Performance: Handling class imbalance boosted recall.
Feature Selection Matters: Removing irrelevant variables improved model efficiency.


Benefits to the Company
Enhanced Customer Retention: Personalized marketing for high-risk customers.
Optimized Marketing Spend: Focused promotions on users likely to churn.
Competitive Advantage: AI-driven customer segmentation for better engagement.


Contributors
Raza Mehdi
