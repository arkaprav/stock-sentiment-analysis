# stock-sentiment-analysis
In this project, a dataset on every day headline about different companies buisness strategies and updates are taken and depending on their reports, the change in stock price is recorded and labeled as 1 or 0 for up or down. Then the data is cleaned and all the headlines are joined to form singular string for each. The text data is vectorized using countvectorized with a ngram range of 2x2. Then the headlines are vectorized using this countvectorizer. The vectorized headline are used as an independent fature and the labels are used as the target feature in the prediction. For prediction, we used a randomcalssifier with 200 estimators and entropy criterion. After prediction,the accuracy reports are -
## Results
### Confusion matrix: 
[[144  42]
[ 13 179]]

### Accuracy score: 
0.8544973544973545

### Classification report : 
               precision    recall  f1-score   support

           0       0.92      0.77      0.84       186
           1       0.81      0.93      0.87       192
           
    accuracy                           0.85       378
   macro avg       0.86      0.85      0.85       378
weighted avg       0.86      0.85      0.85       378

## Conclusion
From the results we can say it is a good model for predicting the stock sentiment
