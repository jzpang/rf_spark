# rf_spark
random forest on spark

In this project, random forest regression and classification models were implemented on Spark with python.

DataSet: Abalone data
Number of Instances: 4177
Number of Attributes: 8
Problem: Predicting the age of abalone from physical measurements.


For random forest regression model with 20 trees:
Root Mean Squared Error (RMSE) on test data = 2.18156
Mean Squared Error (MSE) on test data = 4.75919
R^2 on test data = 0.537818
Mean Absolute Error (MAE) on test data = 1.54974
Based on regression result, it does not show a strong correlation between the features and labels.
For random forest classification model with 20 trees:
Accuracy= 0.271676
Weighted Precision= 0.234333
Weighted Recall= 0.271676
f1 score= 0.271676
Based on accuracy and f1 score, the classification model shows a weak ability on prediction, while considering there are 30 classes in total, the classifier is much better than a random classifier.
