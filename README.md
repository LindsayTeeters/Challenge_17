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
    ![Naive](https://github.com/LindsayTeeters/Challenge_17/blob/main/Resources/Oversampling%20Classification%20Report.png)
    
* Oversampling (SMOTE): 62%
![SMOTE](https://github.com/LindsayTeeters/Challenge_17/blob/main/Resources/Smote%20Classification%20Report.png)

* Undersampling (Cluster Centroids): 51%
![Cluster](https://github.com/LindsayTeeters/Challenge_17/blob/main/Resources/Undersampling%20Imbalanced%20Classification%20Summary.png)

* Combination (SMOTEENN): 51%
![SMOTEENN](https://github.com/LindsayTeeters/Challenge_17/blob/main/Resources/Combo%20Clas%20Sum.png)

* Ensemble (B Random Forest Clas): 78%
![EBFC](https://github.com/LindsayTeeters/Challenge_17/blob/main/Resources/Risk%20Ensemble%20Classification%20Report.png)

* Ensemble (EE AdaBoost Clas): 93%
![EEADBC](https://github.com/LindsayTeeters/Challenge_17/blob/main/Resources/Risk%20Ensemble%20AdaBoost%20Classification%20Report.png)




<b><i> Precision Scores </i></b>(Reflected in picture above)

* Naive Random Oversampling(RandomOverS): 
    - High Risk: .01%
    - Low Risk:   1%
* Oversampling (SMOTE): 
    - High Risk: .01%
    - Low Risk:  1%
* Undersampling (Cluster Centroids): 
    - High Risk: .01%
    - Low Risk:   1%
    ![Cluster](
* Combination (SMOTEENN): 
    - High Risk: .01%
    - Low Risk:   1%
* Ensemble (B Random Forest Clas):
    - High Risk: .04%
    - Low Risk:   1%
* Ensemble (EE AdaBoost Clas): 
    - High Risk: .07%
    - Low Risk:   1%




<b><i> Recall Scores </i></b>(Reflected in picture above)

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
    - High Risk: .04%
    - Low Risk:   1%
* Ensemble (EE AdaBoost Clas): 
    - High Risk: .07%
    - Low Risk:   1%

----------------------------------------------------------------------------------------------------------------

## Summary

The algorithms that had the best accuracy rate was the Easy Ensemble AdaBoost(EEAB) with 93%. The runner up was Ensemble Balanced Random Forest Classifer with 78%. The highest high-risk recalled loans was EEAB with 91%. The lowest high-risk recalled loans was SMOTE with 60%. The Easy Ensemble algorithms preformd much better than the others. A reccomendation that I would make would be to slightly adjust the classification on the Easy Ensembles.  


