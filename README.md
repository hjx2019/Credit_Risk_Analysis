# Credit_Risk_Analysis

> M17 In this project, the performances of all the supervised machine learning models are used. The analysis and conclusions are as below.

## Overview of the analysis

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, different techniques are employed to train and evaluate models with unbalanced classes. 

> Libraries: imbalanced-learn scikit-learn

## Results

### Naive Random Oversampling

  * accuracy: 0.6870331414572701
  * precision: 0.99
  * recall: 0.60

### SMOTE Oversampling

  * accuracy: 0.6624818234863711
  * precision: 0.99
  * recall: 0.69

### Undersampling

  * accuracy: 0.6624818234863711
  * precision: 0.99
  * recall: 0.52

### Combination (Over and Under) Sampling

  * accuracy: 0.6447701423556762
  * precision: 0.99
  * recall: 0.57

### Balanced Random Forest Classifier

  * accuracy: 0.9996784377923293
  * precision: 1.00
  * recall: 1.00

### Easy Ensemble AdaBoost Classifier

  * accuracy: 1.0
  * precision: 1.0
  * recall: 1.0

## Summary

 * Over Sampling and Under Sampling has lower accuracy and recall scores.
 * The Easy Ensemble AdaBoost Classifier will be employed.
