# Creditcard_Fraud_Detection_using_Machine_Learning
Credit card fraud detection uses machine learning and rule-based techniques to identify suspicious transactions based on patterns, anomalies, and user behavior. It helps prevent unauthorized access and financial losses by flagging potentially fraudulent activities in real-time.
Here's the modified version of your **Credit Card Fraud Detection Using Machine Learning** document with improved readability, grammar, and structure.  

## ** Abstract**  
Credit card fraud is a significant issue, leading to billions of dollars in losses annually. Machine learning offers a powerful approach to detecting fraudulent transactions by identifying suspicious patterns. Credit card fraud involves either the physical loss of a credit card or unauthorized access to sensitive credit card information. Various machine learning algorithms can be utilized for fraud detection. This project aims to develop a machine learning model trained on historical transaction data and tested on unseen transactions to improve fraud detection accuracy.  

**Keywords**: Credit Card Fraud Detection, Fraudulent Transactions, K-Nearest Neighbors, Support Vector Machine, Logistic Regression, Decision Tree.  

## ** Overview**  
With the increasing use of credit cards in daily transactions, ensuring security has become a major concern for credit card companies. According to **credit card statistics (2021)**, there were **2.8 billion credit card users worldwide in 2019**, and **70% of users owned a single card**. Reports indicate that **credit card fraud in the U.S. increased by 44.7% in 2020**.  

There are two primary types of credit card fraud:  
1. **New Account Fraud** – An identity thief opens a credit card account under another person's name. Cases of this fraud type increased by **48% in 2020**.  
2. **Existing Account Fraud** – An identity thief gains unauthorized access to an existing account, usually by stealing credit card information. Cases of this fraud type increased by **9% in 2020** (*Daly, 2021*).  

These alarming statistics highlight the urgency of developing an analytical solution using machine learning to detect fraudulent transactions efficiently.  

## ** Project Goals**  
The primary objective of this project is to detect fraudulent credit card transactions to prevent customers from being charged for unauthorized purchases. This is achieved by:  
- Implementing multiple machine learning algorithms for fraud detection.  
- Comparing the performance of different models based on accuracy and other evaluation metrics.  
- Visualizing results through graphs and performance metrics.  
- Reviewing existing research and techniques for fraud detection.  

## ** Data Source**  
The dataset was obtained from **Kaggle** and consists of **transactions made by European credit card users over two days in 2013**. It includes:  
- **31 attributes** and **284,808 transactions**.  
- **28 anonymized numerical features**, transformed using PCA for privacy.  
- **3 main attributes**:  
  - `Time` – Time elapsed between the first transaction and the current transaction.  
  - `Amount` – The transaction amount.  
  - `Class` – Indicates whether a transaction is fraudulent (`1`) or not (`0`).  

**Dataset Source**: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  

## ** Machine Learning Algorithms Used**  
The following algorithms were implemented for fraud detection:  
- **K-Nearest Neighbors (KNN)**  
- **Logistic Regression (LR)**  
- **Support Vector Machine (SVM)**  
- **Decision Tree (DT)**  

Each model was evaluated based on its accuracy, precision, recall, and F1-score to determine the most effective approach for fraud detection.   

# ** Future Work**  
To improve the model’s effectiveness, the following enhancements can be considered:  
- Testing on diverse datasets of varying sizes and sources.  
- Optimizing the data-splitting ratio to enhance model performance.  
- Integrating location-based tracking by merging telecom data to detect fraudulent transactions based on the cardholder's real-time location.  
  - Example: If a transaction is made in **Abu Dhabi** while the cardholder's phone location is in **Dubai**, it could be flagged as a fraudulent transaction.  

 **Conclusion**  
The goal of this project was to determine the most effective machine learning model for credit card fraud detection. After implementing and evaluating four different models, the K-Nearest Neighbors (KNN) and Decision Tree (DT) algorithms achieved the highest accuracy, successfully detecting fraudulent transactions. This system enhances security and ensures a safer, fraud-free experience for credit card users. 
