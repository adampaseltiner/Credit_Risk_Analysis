# Credit_Risk_Analysis

## Overview

The purpose of this project was to analyze credit risk using various machine learning models. The models used were: RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier.

## Results
In the images below, the balanced accuracy scores and the precision and recall scores of all six machine learning models are highlighted, respectively.

### Random Over Sampler
![RandomOverSampler](https://user-images.githubusercontent.com/82347825/130170911-8143cb23-d5af-4c16-9ffc-598e4a88ceaa.png)


### SMOTE
![SMOTE](https://user-images.githubusercontent.com/82347825/130170915-5d700823-66d0-4de1-b5a7-b8191bfe0b74.png)


### Cluster Centroids
![ClusterCentroids](https://user-images.githubusercontent.com/82347825/130170921-8ab6166a-64a8-425e-a7b1-e54327dd38a0.png)


### SMOTEENN
![SMOTEENN](https://user-images.githubusercontent.com/82347825/130170928-bf6a01bc-740a-429a-9385-8202a7956669.png)


### Balanced Random Forest Classifier
![BalancedRandomForestClassifier](https://user-images.githubusercontent.com/82347825/130170934-2286550e-46f5-4f2f-b9bc-71e141211ec9.png)


### Easy Ensemble Classifier
![EasyEnsembleClassifier](https://user-images.githubusercontent.com/82347825/130170938-53d967cd-96f1-4b11-9829-975bdd1c58f6.png)


## Summary
Of the six models we used, the Easy Ensemble Classifier model proves to be the best model to analyze credit risk since the precision, recall and accuracy scores were the closest to 1. Also, the f1 score (which can be seen as a summary statistic of precision and recall) on the Easy Ensemble Classifier was the highest of all the models at 0.97.

Alternatively, the worst performing model was the Cluster Centroids model with overall low precision and recall scores and an f1 score of only 0.60. 
