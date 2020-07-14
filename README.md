# Spam-Classifier-Ensemble-Methods
This repository contains an ipython jupyter notebook of training and test the ensemlble methods on to classify spam messages using this [`dataset`](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection).
<br>
<br>
# Model Used
I have tried three classification models
1. Random Forest Classifier
2. Bagging Classifer
3. AdaBoost Classifier

The best one was AdaBoost as it had highest accurancy and F-score.
# Conclusion
The resulting scores of esemble methods are following: <br>
Accuracy score for Bagging Classifier : 0.9748743718592965<br>
Precision score Bagging Classifier : 0.9166666666666666<br>
Recall score Bagging Classifier : 0.8918918918918919<br>
F1 score Bagging Classifier : 0.9041095890410958<br>
<br>
Accuracy score for Random Forest Classifier : 0.9806173725771715<br>
Precision score Random Forest Classifier : 1.0<br>
Recall score Random Forest Classifier : 0.8540540540540541<br>
F1 score Random Forest Classifier : 0.9212827988338192<br>
<br>
Accuracy score for Ada Boost Classifier : 0.9770279971284996<br>
Precision score Ada Boost Classifier : 0.9693251533742331<br>
Recall score Ada Boost Classifier : 0.8540540540540541<br>
F1 score Ada Boost Classifier : 0.9080459770114943<br>
<br>
For the three methods they are nearly the same.<br>
# References
The dataset for this project originates from the UCI Machine Learning Repository. The SMS Spam Collection is a public set of SMS labeled messages that have been collected for mobile phone spam research. <br>
That can be found [`here`](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)
