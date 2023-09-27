# CREDIT-CARD-FRAUD-DETECTION
This project is about detecting credit card fraud using logistic regression. The project uses a dataset of credit card transactions and builds a model to predict whether a transaction is fraudulent or not.

Dataset:
The dataset used in this project is the Credit Card Fraud Detection dataset which contains credit card transactions made by European cardholders. The dataset contains 31 columns, with 28 anonymized features, 'Time', 'Amount', and 'Class' (1 for fraudulent transactions, 0 otherwise).

Libraries Used:

- Pandas: for data manipulation and analysis
- NumPy: for numerical operations
- Matplotlib and Seaborn: for data visualization
- Scikit-learn: for machine learning tasks such as data preprocessing, model selection, and evaluation.

Conclusion:
- The logistic regression model was able to achieve an accuracy score of 99.86% on the testing set, making it a good candidate for detecting credit card fraud. However, the dataset used in this project is imbalanced with only 0.172% of fraudulent transactions, which may not be representative of the real world. Further improvements can be made by using more sophisticated techniques such as anomaly detection or neural networks.
