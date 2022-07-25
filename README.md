# Challenge_17


<p align="center" width="100%">
    <img width="55%" src="https://github.com/LindsayTeeters/Challenge_17/blob/main/Resources/CreditRiskTiles.png">
</p>


## Overview

Jill with LendingClub has asked us to help her with evaluating models for credit risk by utilizing imbalanced-learn and scikit-learn libraries. Algorithms we used in oversampling was RandomOverSampler and SMOTE. Algorithms we used in undersampling models was ClusterCentroid. After completing these two, we then tried a combination approach and used SMOTTEENN. Once evaluated, we used two different models (BalancedRandomForestClassifer and EasyEnsembleClassifier) to predict the credit risk.

----------------------------------------------------------------

## Results
<b><i> Balanced Accuracy Scores </i></b>

* Naive Random Oversampling(RandomOverS): 65%
* Oversampling (SMOTE): 62%
* Undersampling (Cluster Centroids): 51%
* Combination (SMOTEENN): 51%
* Ensemble (B Random Forest Clas): 78%
* Ensemble (EE AdaBoost Clas): 93%

<b><i> Precision Scores </i></b>

* Naive Random Oversampling(RandomOverS): 
    - High Risk: .01%
    - Low Risk:   1%
* Oversampling (SMOTE): 
    - High Risk: .01%
    - Low Risk:  1%
* Undersampling (Cluster Centroids): 
    - High Risk: .01%
    - Low Risk:   1%
* Combination (SMOTEENN): 
    - High Risk: .01%
    - Low Risk:   1%
* Ensemble (B Random Forest Clas):
    - High Risk: .04%
    - Low Risk:   1%
* Ensemble (EE AdaBoost Clas): 
    - High Risk: .07%
    - Low Risk:   1%

<b><i> Recall Scores </i></b>

* Naive Random Oversampling(RandomOverS): 
    - High Risk: .62%
    - Low Risk:  .68%
* Oversampling (SMOTE): 
    - High Risk: .59%
    - Low Risk:  .66%
* Undersampling (Cluster Centroids): 
    - High Risk: .60%
    - Low Risk:  .43%
* Combination (SMOTEENN): 
    - High Risk: .60%
    - Low Risk:  .43%
* Ensemble (B Random Forest Clas):
    - High Risk: 
    - Low Risk:   
* Ensemble (EE AdaBoost Clas): 
    - High Risk: 
    - Low Risk:   
