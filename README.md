# **Credit Risk Analysis:**

## *Overview of the Analysis:*
    -The purpose of this analysis was to evaluate credit risk with the use of machine learning models. 
    -Additionally, there was an evailation on the performance of these machine learning models.


## *Results:*

### -Naive Random Oversampling Model:
        -This model has an accuracy score of about 65%
        -This model's high_risk had a precision score of 1% and a recall score of 61%
        -This model's low_risk had a precision score of 100% and a recall score of 68%

![Naive Random Oversampling Model](/data/balanced_random_oversampling_model.png)
    
### -SMOTE Oversampling Model:
        -This model has an accuracy score of about 62%
        -This model's high_risk had a precision score of 1% and a recall score of 61%
        -This model's low_risk had a precision score of 100% and a recall score of 64%

![SMOTE Oversampling Model](/data/SMOTE_oversampling_model.png)

### -Cluster Centroids Undersampling Model:
        -This model has an accuracy score of about 51%
        -This model's high_risk had a precision score of 1% and a recall score of 60%
        -This model's low_risk had a precision score of 100% and a recall score of 43%
        
![Cluster Centroids Undersampling Model](/data/cluster_centroids_undersampling_model.png)
        
### -SMOTEENIN Combination Sampling Model:
        -This model has an accuracy score of about 64%
        -This model's high_risk had a precision score of 1% and a recall score of 70%
        -This model's low_risk had a precision score of 100% and a recall score of 58%
        
![SMOTEENIN Combination Model](/data/SMOTEENIN_combination_model.png)
        
### -Balanced Random Forest Classifier Model:
        -This model has an accuracy score of about 79%
        -This model's high_risk had a precision score of 4% and a recall score of 67%
        -This model's low_risk had a precision score of 100% and a recall score of 91%

![Balanced Random Forest Classifer Model](/data/balanced_random_forest_classifer_model.png)
        
### -Easy Ensemble AdaBoost Classifier Model:
        -This model has an accuracy score of about 93%
        -This model's high_risk had a precision score of 7% and a recall score of 91%
        -This model's low_risk had a precision score of 100% and a recall score of 94%
        
![Easy Ensemble Adaboost Classifer Model](/data/easy_ensemble_adaboost_classifer_model.png)


## *Summary:*
    -Overall the Easy Ensemble Adaboost Classifer Model performed the best out of all the models, with the highest precision score of 7% and highest recall score of 91% for the high_risk group. This means that there is a 7% chance that people who were flagged as high risk actually are high risk and a 91% chance that if someone is high risk, that this model will catch it.
