# Customer-Churn-Prediction

In this data science project, we focused on predicting customer churn using a dataset containing various customer attributes and whether they exited or not. The dataset includes features like credit score, geography, gender, age, tenure, balance, number of products, credit card status, membership activity, and estimated salary.

Key Findings:
Exploratory Data Analysis (EDA):

We explored the dataset to understand the distribution of features and the relationship between different variables.
Investigated factors that might contribute to customer churn, such as age, tenure, and balance.
Data Preprocessing:

Handled missing values, categorical encoding (e.g., one-hot encoding), and feature scaling (standardization) to prepare the data for modeling.
Model Development:

Trained and evaluated two machine learning models for customer churn prediction:
Random Forest Classifier (rfc)
Decision Tree Classifier (dtree)
Model Evaluation:

Assessed model performance using classification metrics and regression metrics:
Precision, recall, F1-score, and support for classifying churned (1) and retained (0) customers.
Accuracy score to measure overall model accuracy.
Mean Absolute Error (MAE) to quantify the average magnitude of errors.
R2 Score to evaluate the proportion of variance explained by the model.
Model Performance:
Random Forest Classifier:
Achieved an accuracy of 86.8% with a weighted F1-score of 0.85.
Demonstrated higher precision and recall for predicting retained customers (class 0) compared to churned customers (class 1).
Recommendations and Insights:
Feature Importance:

Identify important features that contribute significantly to predicting customer churn (e.g., tenure, balance, age).
Use feature importance analysis to understand factors influencing customer retention.
Improvement Strategies:

Explore additional techniques (e.g., feature engineering, ensemble methods) to enhance model performance and address class imbalance.
Business Implications:

Provide actionable insights to stakeholders for customer retention strategies based on model predictions.
Implement targeted marketing or customer engagement initiatives to reduce churn rates.
Limitations and Future Work:
Imbalanced Dataset:
Address class imbalance to improve model sensitivity towards predicting churned customers.
Model Refinement:
Experiment with hyperparameter tuning and model optimization techniques to enhance predictive performance.
In conclusion, this project demonstrated the application of machine learning techniques for customer churn prediction, providing valuable insights for businesses to proactively manage customer retention and optimize customer relationships. Further refinement and exploration can lead to more accurate and actionable predictive models tailored to specific business needs.
