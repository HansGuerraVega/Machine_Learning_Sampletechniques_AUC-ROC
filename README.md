# Project Description
Beta Bank's customers are leaving, little by little, every month. Bankers have discovered that it is cheaper to save existing customers than to attract new ones.

We need to predict whether a customer will leave the bank soon. You have data on past customer behavior and contract terminations with the bank.

Create a model with the highest possible F1 value. To pass the review, you need an F1 value of at least 0.59. Check F1 for the test set.

In addition, you must measure the AUC-ROC metric and compare it to the F1 value.

## Project Instructions
Download and prepare the data.
Examine class balance. Train the model without considering the imbalance. Briefly describe your findings.
Improve model quality. Use at least two approaches to correct class imbalance. Use training and validation sets to find the best model and the best set of parameters. Train different models on the training and validation sets. Find the best one. Briefly describe your findings.
Conduct the final test.

## Data Description
You can find the data in the Churn.csv file.

Characteristics:

RowNumber: Data string index
CustomerId: Unique customer identifier
Surname: Last name
CreditScore: Credit score
Geography: Country of residence
Gender: Sex
Age: Age
Tenure: Period over which a customer's fixed-term deposit has matured (years)
Balance: Account balance
NumOfProducts: Number of banking products used by the customer
HasCrCard: Customer has a credit card (1 - yes; 0 - no)
IsActiveMember: Customer activity (1 - yes; 0 - no)
EstimatedSalary: Estimated salary

Target:

Exited: Customer has left (1 - yes; 0 - no)
