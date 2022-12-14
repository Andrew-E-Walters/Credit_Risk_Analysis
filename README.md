# Credit_Risk_Analysis

## Overview of the analysis
Credit risk is an unbalanced classification problem, as good loans easily outnumber risky loans. We will need to employ different techniques to train and evaluate models with unbalanced classes We need to use libraries to build and evaluate models using resampling. We will then compare the machine learning modials and determine which is the best predictor of credit risk. First, we will use the oversampling RandomOverSampler and SMOTE algorithms, and then you’ll use the undersampling ClusterCentroids algorithm, then we will train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. 


## Results

### The Six Machine Learning Models

#### Calculated the balanced accuracy score
* Random OverSampler: 0.646602844334948
* SMOTE Oversampling: 0.6630664820457723 
* Random UnderSampler using Cluster Centroids: 0.6630664820457723
* Combination (Over and Under) Sampling using SMOTEENN: 0.5447339051023905
* Balanced Random Forest Classifier: NA
* Easy Ensemble AdaBoost Classifier: NA

#### Imbalanced classification report


*             Random Oversampler:
![](https://github.com/Andrew-E-Walters/Credit_Risk_Analysis/blob/main/Random%20Oversampling.png)


*             SMOTE Oversampling:           
![](https://github.com/Andrew-E-Walters/Credit_Risk_Analysis/blob/main/Smote%20oversampling.png)


*             Random UnderSampler using Cluster Centroids:
![](https://github.com/Andrew-E-Walters/Credit_Risk_Analysis/blob/main/Cluster%20Centroids.png)


*           Combination (Over and Under) Sampling using SMOTEENN:
![](https://github.com/Andrew-E-Walters/Credit_Risk_Analysis/blob/main/combo%20over%20and%20under.png)


*           Balanced Random Forest Classifier:
NA


*           Easy Ensemble AdaBoost Classifier: 
NA

## Summary

Overall the diffrent models got us various levels of accuracy, precison, and recall scores. When we take a look at how the models compare to the original reuslts it seems that there are some that perform better than others. These models are relatively in the same range of one another when it comes to accuracy as they do not break the threshold that most would consider to be a good level of accuracy. 

#### Recomendation
I would recommend using the SMOTE Oversampling as it gave the best accuracy score, and it also had the highest combination of precison, and recall scores.However I would say that none of the accuracy scores hit the 70% threshold so they are all not at the level that we would like to see. There will be cases where they are not good predictors at choosing low vs high risk credit cards and a better model should be chosen. 
