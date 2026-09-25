# CustomerChurnPrediction
Machine learning project predicting customer churn and identifying opportunities to improve customer retention.

Overview

In this project, I worked with a telecommunications customer dataset to predict whether a customer is likely to churn based on their account information and usage patterns. The goal was to use customer data to identify customers at risk of leaving and support potential retention strategies.

What I Did
Explored and cleaned a dataset of 7,183 customer records
Handled missing values and prepared categorical features
Split the data into training and testing sets
Standardized features using StandardScaler
Built a Logistic Regression model to predict customer churn
Evaluated performance using multiple classification metrics
Results

The model achieved:

Accuracy: 65.76%
Precision: 61.31%
Recall: 54.55%
F1 Score: 57.73%
Business Impact & Interpretation

The model can help identify customers who may be at risk of leaving, allowing a company to take action earlier through targeted offers, improved service, or other retention strategies.

The model produced 280 false negatives, meaning some customers who actually churned were not identified. This could result in missed opportunities to retain those customers. It also produced 212 false positives, which could lead to unnecessary retention efforts or discounts for customers who were not going to leave.

For this use case, improving recall would be important because identifying more customers who are actually at risk could help reduce missed retention opportunities.

Potential Improvements

Future improvements could include testing additional machine learning models, adding more customer behavior or satisfaction data, tuning the model, and improving recall to better identify customers at risk of churn.

Tools

Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn · Jupyter Notebook
