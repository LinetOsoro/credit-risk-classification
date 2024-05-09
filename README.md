## Credit Risk Classification

# Split the Data into Training and Testing Sets
Create Features and Labels: Create the labels set (y) from the “loan_status” column and the features (X) DataFrame from the remaining columns.
Split the data into training and testing datasets using train_test_split.

# Create a Logistic Regression Model with the Original Data
Use logistic regression to fit a model using the training data (X_train and y_train).
Save predictions for the testing data labels using the testing feature data (X_test) and the fitted model.
Generate a confusion matrix.
Print the classification report.

# Analysis
Assess how well the logistic regression model predicts both healthy (0) and high-risk (1) loan labels.

# Write a Credit Risk Analysis Report

### Overview
Explain the purpose of the analysis, which is to assess credit risk using machine learning techniques, particularly logistic regression.

### The Results
Describe accuracy score, precision score, and recall score of the machine learning model in a bulleted list.

### Summary
Summarize the machine learning model results. Justify recommending the model for use by the company or provide reasoning if not recommended.

### Conclusion
Conclude the analysis, considering the trade-offs between precision, recall, and the company's risk tolerance.
