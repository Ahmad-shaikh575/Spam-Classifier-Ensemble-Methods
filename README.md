# Spam-Classifier-Ensemble-Methods
This repository contains an ipython jupyter notebook of training and test the ensemlble methods on to classify spam messages using this [`dataset`](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection).


# Model Used
I have tried three classification models
1. Random Forest Classifier
2. Bagging Classifer
3. AdaBoost Classifier

The best one was AdaBoost as it had highest accurancy and F-score.
# Conclusion
The resulting scores of esemble methods are following:
Accuracy score for Bagging Classifier : 0.9748743718592965
Precision score Bagging Classifier : 0.9166666666666666
Recall score Bagging Classifier : 0.8918918918918919
F1 score Bagging Classifier : 0.9041095890410958

Accuracy score for Random Forest Classifier : 0.9806173725771715
Precision score Random Forest Classifier : 1.0
Recall score Random Forest Classifier : 0.8540540540540541
F1 score Random Forest Classifier : 0.9212827988338192

Accuracy score for Ada Boost Classifier : 0.9770279971284996
Precision score Ada Boost Classifier : 0.9693251533742331
Recall score Ada Boost Classifier : 0.8540540540540541
F1 score Ada Boost Classifier : 0.9080459770114943

For the three methods they are nearly the same.
# References
The dataset for this project originates from the UCI Machine Learning Repository. The SMS Spam Collection is a public set of SMS labeled messages that have been collected for mobile phone spam research. 
That can be found [`here`](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)
