# Credit_Risk_Analysis
## Overview of the analysis:

The purpose of this analysis was to create a supervised machine learning model that could accurately predict credit risk. In order to complete this task, I used 6 different methods, which are:

1. Naive Random Oversampling
2. SMOTE Oversampling
3. Cluster Centroid Undersampling
4. SMOTEENN Sampling
5. Balanced Random Forest Classifying
6. Easy Ensemble Classifying

Through each of these methods, I split my data into training and testing datasets, and compiled accuracy scores, confusion matries, and classification reports as my results.

## Results

## Naive Random Oversampling
- Accuracy Score: 62.4%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 60%
- Recall Low Risk: 65%

![Naive Random Oversampling](https://user-images.githubusercontent.com/88256967/144768673-ac3e3556-c3ea-40da-a386-95d0a5cb727e.PNG)

## SMOTE Oversampling
- Accuracy Score: 65.1%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 64%
- Recall Low Risk: 66%

![SMOTE OVERSAMPLING](https://user-images.githubusercontent.com/88256967/144768691-2c767773-d4bf-44ca-b422-fcb7e360fa4f.PNG)

## Cluster Centroid Undersampling
- Accuracy Score: 51.6%
- Precision High Risk: 0%
- Precision Low Risk: 100%
- Recall High Risk: 60%
- Recall Low Risk: 43%

![UNDERSAMPLING](https://user-images.githubusercontent.com/88256967/144768727-9966f107-c1f4-4017-b19e-376471dc84ee.PNG)

## SMOTEENN Sampling
- Accuracy Score: 61.6%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 69%
- Recall Low Risk: 54%

![Combination Sampling](https://user-images.githubusercontent.com/88256967/144768791-860b38ad-0cb5-4f70-b243-e85ba234f841.PNG)

## Balanced Random Forest Classifying
- Accuracy Score: 78.7%
- Precision High Risk: 4%
- Precision Low Risk: 100%
- Recall High Risk: 67%
- Recall Low Risk: 91%

![BALANCED RANDOM FOREST CLASSIFIER](https://user-images.githubusercontent.com/88256967/144768814-e415f120-b691-4024-873c-441e6cdae677.PNG)

## Easy Ensemble Classifying
- Accuracy Score: 92.5%
- Precision High Risk: 7%
- Precision Low Risk: 100%
- Recall High Risk: 91%
- Recall Low Risk: 94%
- 
![Easy Ensemble Adaboost](https://user-images.githubusercontent.com/88256967/144768863-b5ed93c7-07a2-482c-9b57-e08afa455db1.PNG)

## Summary

All the models used to perform the credit risk analysis show weak precision in determining if a credit risk is high.
The Ensemble models brought a lot more improvment specially on the sensitivity of the high risk credits.
The EasyEnsembleClassifier model shows a recall of 92% so it detects almost all high risk credit. On another hand, with a low precision, a lot of low risk credits are still falsely detected as high risk which would penalize the bank's credit strategy and infer on its revenue by missing those business opportunities.

In conclusion, I would not recommend the bank to use any of these models to predict credit risk.


