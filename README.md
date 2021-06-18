# Credit_card_fraud_detection

The dataset is sythetic dataset contains transactions in a certain amount of period. There are The data has 786363 data points with 29 columns. The rate of fraud transactions to total transactions is around 1.6%. The dataset is highly imbanlanced. Main challenge of the task is to deal with highly imbalanced dataset. Also, dataset contains multiple categorical data, how to prepross is a key as well. 

Here I have used GMBs such as catboost and xgboost model internally deal with missing data, and use catboost internally deal with categorical data. For xgboost, I used label encoder instead of one-hot encoder. Final F1 score is around 0.3 and accuracy is around 98.6%. More future work can be improve feature engineering, create more relevant features and to try other techniques such as under-sampling and over-sampling to deal with imbalance issue.
