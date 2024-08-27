# Bank-Customer-Churn-Prediction
The project successfully developed a predictive model for bank customer churn, using a dataset with features such as credit score and age.

# Project Overview
The project aimed to develop a predictive model for bank customer churn, which is the phenomenon where customers leave or stop using a bank’s services. The objective was to build a model that accurately predicts whether a customer will churn or not based on various features such as credit score, geography, age, balance, and more.

# Approach
Data Preparation:

# Data Encoding:
Categorical features like Geography and Gender were converted into numerical formats to be used in machine learning algorithms.
Feature Scaling: Features were scaled to ensure uniformity and to improve the performance of the model, particularly for algorithms sensitive to feature scaling.
Handling Imbalanced Data:

# Under-Sampling: 
A technique where the majority class (non-churned customers) was reduced to match the size of the minority class (churned customers). This helps to balance the dataset but might lead to loss of valuable data.
Over-Sampling: Techniques like Random Over-Sampling were applied to increase the number of minority class samples by duplicating or generating synthetic examples. This method helps to balance the dataset without losing information.
Model Building:

# Support Vector Machine (SVM) Classifier:
Used as the core model for classification. SVM is effective in high-dimensional spaces and works well for classification tasks.
Hyperparameter Tuning: Grid search was employed to find the optimal hyperparameters for the SVM model, enhancing its performance.
Model Evaluation:

# Random Over-Sampling: 
This approach yielded the highest accuracy (92%) and precision among the methods tested. Precision, in this context, measures the proportion of correctly identified churned customers out of all customers predicted to churn, indicating a strong model performance in identifying true positives.
Results
The Random Over-Sampling technique demonstrated the best results, achieving the highest accuracy and precision. This indicates that the model trained with this approach was the most effective in correctly predicting whether customers would churn, reducing false positives and negatives.

# Summary
The project involved preprocessing data, addressing class imbalance through various techniques, and optimizing an SVM classifier. The Random Over-Sampling method provided the best performance, highlighting its effectiveness in improving model accuracy and precision for predicting customer churn. This model can now be used to develop strategies for customer retention and reduce churn rates.
