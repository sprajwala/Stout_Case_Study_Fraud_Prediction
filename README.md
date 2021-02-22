# Stout_Case_Study_Fraud_Prediction
This is the repo for all my code as part of this case study

-> Performed Exploratory data analysis on 47 million rows of data from the "Synthetic Financial Datasets For Fraud Detection" by Kaggle:
https://www.kaggle.com/ntnu-testimon/paysim1

-> Profiled the dataset and found issues with it. Created visualizations on the full dataset to confirm these issues and answer other questions to help in data cleaning.

-> Cleaned the data by removing unwanted information, outliers and by balancing the dataset. 

-> Performed feature engineering by normalizing the "amount" column and encoding categorical variables.

-> Performed prediction on pre-processed dataset using Logistic Regression and Random Forest algorithms. Visualized the results before and after data cleaning for both models.

Results:

Evaluation Metrics for Logistic Regression
Accuracy	0.9034356576539947
Precision	0.8523560209424084
Recall	0.9791499599037691

Classification Report for Random Forest
Precision	Recall	F1-score	Support
0	1.00	   0.99	    0.99	   2425
1	0.99	   1.00	    0.99	   2494

Accuracy			            0.99	4919
Macro Avg	    0.99	0.99	0.99  4919
Weighted Avg	0.99	0.99	0.99	4919
