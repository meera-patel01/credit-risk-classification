# credit-risk-classification
--------------------------
GITHUB DIRECT CODE LINK (credit_risk_classification.ipynb): https://github.com/meera-patel01/credit-risk-classification/blob/main/credit_risk_classification.ipynb

## Credit Risk Analysis Report
1. An overview of the analysis:
    - The purpose of this credit risk classification analysis is to use various techniques to train and evaluate a model based on loan risk and build a model that can identify the creditworthiness of borrowers.
2. The results:
    - Accuracy score: The balanced accuracy score for this ML model is 96.7% which rounds up to 97% which means the percentage of correctly predicted observations to the total number of observations is 97%.
    - Precision score: The precision score for this ML model is 92% which means the percentage of correctly predicted positive observations to the total predicted positive observations is 92%.
    - Recall score: The recall score for this ML model is 96.5% which rounds up to 97% which means the percentage of correctly predicted positive observations to all predicted observations for that class is 97%.
3. A summary:
    - This ML model has more than 90% accuracy, precision, and recall for the creditworthiness of borrowers so I would recommend this model for use by the company. The results can aid the company in its business by adding information to the company's risk profile.

## Background
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Instructions
The instructions for this Challenge are divided into the following subsections:
- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Write a Credit Risk Analysis Report

### Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:
1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
3. Split the data into training and testing datasets by using train_test_split.

### Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Evaluate the model’s performance by doing the following:
    - Generate a confusion matrix.
    - Print the classification report.
4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

### Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework.
1. An overview of the analysis: Explain the purpose of this analysis.
2. The results: Using a bulleted list, describe the accuracy score, the precision score, and the recall score of the machine learning model.
3. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
