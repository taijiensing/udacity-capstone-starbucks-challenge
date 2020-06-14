# Udacity Data Scientist Nanodegree
# Starbucks Capstone Challenge

# 1. Motivation
This is a the capstone project for Udacity's Data Scientist Nanodegree program. The challenge data set contains simplified/simulated data that mimics customer behavior on the Starbucks rewards mobile app.

Every few days, each customer with the Starbucks mobile app would receive personalized offers such as a discount, BOGO (buy one get one free) or merely an advertisement for a drink. This means different users would receive different offers at different timings. Some users might not receive any offer during certain weeks.

This project will combine (1) transaction, (2) demographic and (3) offer data to determine which demographic groups respond best to which offer type. A pipeline is built all the way from data cleansing, data preprocessing, data analysis, all the way to the final almagation of the data sets to serve as inputs to a machine learning model that will enable us to predict offer success.

# 2. Major Libraries Used (and not limited to):
 * sklearn.preprocessing (MinMaxScaler, MultiLabelBinarizer, LabelBinarizer)
 * sklearn.metrics (accuracy_score, f1_score, fbeta_score, make_scorer)
 * sklearn.ensemble (RandomForestClassifier)
 * sklearn.linear_model (LogisticRegression)
 * sklearn.model_selection (train_test_split, GridSearchCV, RandomizedSearchCV)

# 3. File Description:
 * Main Coding: Starbucks_Capstone_notebook - Submission.ipynb
 * HTML version: Starbucks_Capstone_notebook - Submission.html

# 4. Summary of Results:
The project shows that even a simple Machine Learning model like Logistic Regression has the potential to increase revenues, as shown by the ability to categorize customers according to their demographics and usage behavior.
We have also shown that a Random Forest model gave us a better performance, which is then further optimized by grid search. 

Detailed workings and explanations are contained within Jupyter Notebook in this repository: 
Starbucks_Capstone_notebook - Submission.ipynb

# 5. Links:

### Medium
https://medium.com/@taijiensing/starbucks-capstone-challenge-predicting-customer-offer-success-4ea63cadbef7

### Github
https://github.com/taijiensing/udacity-capstone-starbucks-challenge
