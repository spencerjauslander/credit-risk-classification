# credit-risk-classification

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Write a Credit Risk Analysis Report

### An overview of the analysis  
1. Explain the purpose of this analysis.
   - The purpose of this analysis is to develop and train a data model that can accurrately predict if a loan is healthy or high-risk. This is useful in the decision making or the confidence of clients.
2. The results.
   - Balanced Accuracy: 95.20479254722232%
   - Precision Score: 92%
   - Recall Score: 95%
3. A Summary.
   - The above accuracy scores are significantly high for a predictive model, allowing businesses to identify the creditworthiness of borrowers.
