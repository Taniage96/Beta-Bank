# Bank Customer Churn Prediction

## Project Description

Beta Bank's customers have been gradually leaving each month. Bankers have discovered that it is cheaper to retain existing customers than to attract new ones.

We need to predict whether a customer will soon leave the bank. You have data on customers' past behavior and termination of contracts with the bank.

Build a model with the maximum possible F1 score. To pass the review, you need an F1 score of at least 0.59. Check the F1 for the test set.

Additionally, you should measure the AUC-ROC metric and compare it with the F1 score.


### Features

* `RowNumber`: data string index
* `CustomerId`: unique customer identifier
* `Surname`: surname
* `CreditScore`: credit score
* `Geography`: country of residence
* `Gender`: gender
* `Age`: age
* `Tenure`: period during which a customer's fixed deposit has matured (years)
* `Balance`: account balance
* `NumOfProducts`: number of bank products used by the customer
* `HasCrCard`: customer has a credit card (1 - yes; 0 - no)
* `IsActiveMember`: customer activity (1 - yes; 0 - no)
* `EstimatedSalary`: estimated salary

### Target

* `Exited`: customer has left (1 - yes; 0 - no)
