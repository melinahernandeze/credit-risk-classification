# Credit Risk Classification

### Overview

This project aims to build a machine learning model for credit risk classification using historical lending activity data from a lending services company. The model will predict the creditworthiness of borrowers based on multiple features.

### Files

- **credit_risk_classification.ipynb**: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- **lending_data.csv**: Dataset of historical lending activity.

### Split the Data into Training and Testing Sets

1. **Read the Data**: Load the lending_data.csv data into a Pandas DataFrame.
2. **Split the Data**: Separate the data into labels (`y`) and features (`X`), and then split them into training and testing datasets using train_test_split.

### Create a Logistic Regression Model with the Original Data

1. **Create the Model**: Import the LogisticRegression model from scikit-learn, assigning a random_state parameter of 1.
2. **Fit the Model**: Train the model using the training data.

### Evaluate the Model

1. **Generate Confusion Matrix**: Use confusion_matrix from scikit-learn to generate a confusion matrix for the model.
2. **Print Classification Report**: Use classification_report from scikit-learn to print the classification report for the model.

### Model Performance

The logistic regression model demonstrates high performance in predicting loan risk, with an accuracy of 99%. It achieves near-perfect precision and recall for healthy loans (label 0) and reasonably high precision and recall for high-risk loans (label 1).

### Recommendation

Based on the strong performance metrics and interpretability, the logistic regression model is recommended for use by the company in assessing loan risk. It effectively identifies both healthy and high-risk loans while maintaining a balance between precision and recall.

Continuous monitoring and validation of the model's performance on new data are advised to ensure its reliability in real-world lending scenarios.

