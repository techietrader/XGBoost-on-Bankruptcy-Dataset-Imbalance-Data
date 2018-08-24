# XGBoost on Bankruptcy Dataset (Imbalance Data)
The given data contains details of various markers and financial ratios of entities.

Target variable is whether the company got bankrupt in the subsequent years or not.

1 - bankrupt 
0 - not bankrupt

## Problem Statement -
Supervised Classification Problem with Imbalance dataset.
Take a look-

![imbalance_data](https://user-images.githubusercontent.com/29548935/44611866-990db680-a821-11e8-9e2e-82bf84e6fbc5.PNG)

In such cases , Accuracy is a misleading evaluation metric and recall becomes very vital.
![recall and precision](https://user-images.githubusercontent.com/29548935/44611954-23eeb100-a822-11e8-8e12-8d1649e6b3ba.PNG)


The efforts made in this file are in and around to improve recall and thereby improving the F1 Accuracy score.
Oversampling is also used to reduce the imbalance somewhat followed by different classifiers training and some hyperparameter tuning using GridSearch.

Enjoy!
