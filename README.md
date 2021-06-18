# Credit_card_fraud_detection

The dataset is a large synthetic dataset that contains transactions in a certain amount of period. There are The data has 786363 data points with 29 columns. The rate of fraud transactions to total transactions is around 1.6%. The dataset is highly imbalanced. The main challenge of the task is to deal with the highly imbalanced dataset. Also, the dataset contains multiple categorical data. How to preprocess is a key as well.

Here I have used GMOs such as catboost and xgboost model internally to deal with missing data and use catboost internally to deal with categorical data. For xgboost, I used label encoder instead of one-hot encoder. The final F1 score is around 0.3, and accuracy is about 98.6%. More future work can improve feature engineering, create more relevant features, and try other techniques such as under-sampling and over-sampling to deal with imbalance issues.
