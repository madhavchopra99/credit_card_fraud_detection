
This uses logistic regression to check the fraundulent transactions.

For more info [click here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Dependencies

* Numpy
* Pandas
* Seaborn
* Scikit Learn
* Matplotlib

## Screenshots

### Average Transaction Value
![Comparing Legit and Fraud Transaction average values](https://raw.githubusercontent.com/madhavchopra99/credit_card_fraud_detection/main/screenshots/comparing_mean_values.png)

### Confusion Matrix
![Confusion Matrix](https://raw.githubusercontent.com/madhavchopra99/credit_card_fraud_detection/main/screenshots/confusion%20matrix.png)


## Aproach

There are no null values present in dataset which ensure high quality of data. Here, we have total 31 vectors for training our model.

In this dataset we have way fewer positive entires compared to negative one.
We are using under-sampling to have equal values for fraud and legit transations. This allow us to have better logistic regression model.
We have 80-20 split between training and test sets.

We training our model using Logistic Regression with newton's method.
Resultant model has accuracy score of 94.41% and confusion matrix is published under "screenshots".



