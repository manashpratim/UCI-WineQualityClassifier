# UCI-WineQualityClassifier

Implementation of Random Forest Classifier - Classify Wine Quality - UCI Dataset. Principal Component Analysis has been used before classification. Best results have been obtained using Random Forest Classifier with n_estimators=700.

# Problem Statement

The goal is to model wine quality based on physicochemical tests. There are two datasets related to red and white wine which are available for download at  http://archive.ics.uci.edu/ml/datasets/Wine+Quality. The classification task is to determine the quality of the wine based on the input features.


# Implementation

First, Principal Component Analysis is done on both the datasets and then Random Forest Classifier is used on both the datasets. Both the datasets are randomly split into 70% train data and 30% test data.

# Results

The red wine dataset gives an accuracy of over 91% with RFC having n_estimators=700. The white wine data set performs slightly better with an accuarcy of over 94% using RFC with n_estimators=700.
