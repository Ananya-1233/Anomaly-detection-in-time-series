# Anomaly-detection-in-time-series
A machine learning approach to detect anomalies in a time series data.


Time series data consists of prices of a certain stock over a period of time that can last as long as a decade.

Within such a duration, it is possible that the stock price might either increase exponentially or plummet. In a way, this phenomenon can be considered as an anomaly.

An anomaly where, the price value preceding it and that succeding it are very far from the price under consideration.

Such anomalies can be catastrophic to a model that is used to predict the stock price for future purposes. It can hinder the model's understanding of the data and can lead to inaccurate predictions in the data.

The code above segments the dataset into chunks of small size for training. The data is already labelled with whether it is an anomaly or not. 

Supervised training is performed using Convolutional Neural Networks using f1-score as the metric for evaluation.

An f1-score of 96.7% is acheived with only 95 misclassifications out of 11325 data points.

