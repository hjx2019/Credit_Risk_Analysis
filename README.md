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

![image](https://user-images.githubusercontent.com/48306359/143512862-9e05adc5-4cbf-4bd8-b189-c621125ca2f9.png)


### SMOTE Oversampling

  * accuracy: 0.6624818234863711
  * precision: 0.99
  * recall: 0.69

![image](https://user-images.githubusercontent.com/48306359/143512889-d6ad5bea-8b12-46b5-933b-bf60503981fb.png)

### Undersampling

  * accuracy: 0.6624818234863711
  * precision: 0.99
  * recall: 0.52

![image](https://user-images.githubusercontent.com/48306359/143512901-98696e24-c63f-4129-bacf-33dc388abe8a.png)

### Combination (Over and Under) Sampling

  * accuracy: 0.6447701423556762
  * precision: 0.99
  * recall: 0.57

![image](https://user-images.githubusercontent.com/48306359/143512918-4aa5eeb7-8d04-4894-8479-9395b9d858b7.png)

### Balanced Random Forest Classifier

  * accuracy: 0.9996784377923293
  * precision: 1.00
  * recall: 1.00

![image](https://user-images.githubusercontent.com/48306359/143512941-18df8147-86fb-4457-a7f2-8bc2f3225227.png)

### Easy Ensemble AdaBoost Classifier

  * accuracy: 1.0
  * precision: 1.0
  * recall: 1.0

![image](https://user-images.githubusercontent.com/48306359/143512963-46fd9f1e-50de-4839-9e69-8f40914dd4f8.png)

## Summary

 * Over Sampling and Under Sampling has lower accuracy and recall scores.
 * The Easy Ensemble AdaBoost Classifier will be employed.
