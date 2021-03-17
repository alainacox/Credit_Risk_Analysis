# Credit_Risk_Analysis
## Overview 
The purpose of this analysis is to use different techniques to train and evaluate models. I will do this by using imbalanced-learn and scikit-learn libraries to resample the dataset. I will do this by:

•	Oversampling the data

•	Undersampling the data

•	Combing the over and under sampled data

•	Comparing the machine learning models 
### Six Machine Learning Models
•	Naive Random Oversampling

•	SMOTE Oversampling

•	Cluster Centroids

•	SMOTEENN

•	Balanced Random Forest Classifier

•	Easy Ensemble AdaBoost Classifier
## Results
### Naive Random Oversampling:
#### Balanced Accuracy Score of 66.73% 

![NRO]( https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/NRO.png) 

![NRO1]( https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/Oversampling.png) 

### SMOTE Oversampling
#### Balanced Accuracy Score of 64.14% 

![SMOTE]( https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/SMOTE.png) 

![SMOTE1]( https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/SMOTE1.png)

### Cluster Centroids Undersampling
#### Balanced Accuracy Score of 45.07% 

![CC]( https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/CC.png)

![CC1]( https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/CLusterCentroids.png)

### SMOTEENN Combined Sampling
#### Balanced Accuracy Score of 58.33% 

![SMT]( https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/SMOTEENIN.png) 

![SMT1]( https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/SMOTEENIN1.png) 


### Balanced Random Forest Classifier
#### Balanced Accuracy Score of 89.96% 

![BRFC](https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/BRFC.png)

![BRFCI]( https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/BalancedRandom.png)

### Easy Ensemble Classifier
#### Balanced Accuracy Score of 92.54% 

![EEABC]( https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/EEABC.png) 

![EEABC1]( https://github.com/alainacox/Credit_Risk_Analysis/blob/main/module%2017/EasyEnsemble.png) 


## Summary
Based on the balanced accuracy score all of the models were above 40%. Each of the models had misclassified high-risk clients. With the given dataset I would have to go with the model that had the ability to truly identify high-risk clients. If I am going based on the statement that I just made, I would have to recommend going with the Easy Ensemble model. 


