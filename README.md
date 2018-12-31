# fraud-detection

## Data
Data can be found on [Kaggle here](https://www.kaggle.com/mlg-ulb/creditcardfraud)
The data has been anonymized for security reasons so we do not know what the individual columns in the df mean. 

## Logistic and Random Forest
Two different methods are provided for determining outliers. Logistic regression and Random Forest classifiers. The RF classifier does slightly better using this dataset. The metrics we use for determining validity are:
- Cohen Kappa Score
- Sensitivity/Recall for Model
- F1 Score for Model
