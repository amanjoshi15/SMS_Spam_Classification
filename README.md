# SMS_Spam_Classification
## Introduction:-
A Machine Learning model to classify SMS Messages as 'spam' or 'ham' using NLP, various ML algorithms like Multinomial Naive Bayes, Support Vector Classifier, Logistic Regression, Decision Tree Classifier and some preprocessing techniques like Stemming, Lemmetization, TF/IDF Vectorization and Count Vectorization achieving a maximum accuracy of 96.90%.
## Accuracy:-
| Text Preprocessing Type              | Multinomial NB | Support Vector Classifier | Logistic Regression | Decision Tree |
|--------------------------------------|----------------|---------------------------|---------------------|---------------|
| TFIDF Vectorization                  | 93.41%         | 96.90%                    | 91.39%              | 94.10%        |
| Count Vectorization                  | 94.59%         | 91.86%                    | 90.39%              | 92.82%        |
| TFIDF Vectorization + Stemming       | 94.48%         | 96.32%                    | 90.87%              | 93.47%        |
| Count Vectorization + Stemming       | 94.32%         | 91.32%                    | 90.10%              | 92.89%        |
| Count Vectorization + Lemmatization  | 94.32%         | 91.34%                    | 89.99%              | 92.75%        |
| TF/IDF Vectorization + Lemmatization | 94.46%         | 96.37%                    | 90.71%              | 94.08%        |
## Dataset:-
The dataset used is the SMS Spam Dataset by UCI Machine Learning.You can download it from [here](https://www.kaggle.com/uciml/sms-spam-collection-dataset/download).
