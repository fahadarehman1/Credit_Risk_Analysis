# Credit Risk Analysis
UW Data Bootcamp - Module 17

### **Overview of the analysis:** 

The ask of this project was to predict credit risk using the supervised machine learning capabilities. The following algorithms and libraries are used in Python to calculate accuracy scores, confusion matrices and classification reports:

**Algorithms/ Classifiers:** LogisticRegression, BalancedRandomForectClassifier, EasyEnsembleClassifier, SMOTE, SMOTEENN, RandomOverSampler, CluserCentroids, etc . . . 

**Libraries:** imbalanced-learn and scikit-lear

### **Results:** 

- **Naive Random Oversampling**

![](C:\Users\Fahad.Rehman\Desktop\UW DataBootcamp\Machine_Learning_Supervised\Naive_Random_Oversampling.PNG)               

Balanced Accuracy is 65%, precision is low for high_risk score. Precision of low_risk score is 100%



- **SMOTE Oversampling**

![](C:\Users\Fahad.Rehman\Desktop\UW DataBootcamp\Machine_Learning_Supervised\SMOTE_Oversampling.PNG) 

Balanced Accuracy is 62%, precision is low for high_risk score. Precision of low_risk score is 100%. The results are very similar to Naive Random oversampling results



- **Undersampling**

![](C:\Users\Fahad.Rehman\Desktop\UW DataBootcamp\Machine_Learning_Supervised\Undersampling.PNG) 

Balanced Accuracy is 62%, precision is low for high_risk score. Precision of low_risk score is 100%. The results are identical to SMOTE oversampling even to the decimal point



- **Combination (Over and Under) Sampling**

![](C:\Users\Fahad.Rehman\Desktop\UW DataBootcamp\Machine_Learning_Supervised\over_and_under_sampling.PNG) 

Balanced Accuracy is 62%, precision is low for high_risk score. Precision of low_risk score is 100%, very similar to SMOTEN and Undersampling results



- **Balanced Random Forest Classifier**

![](C:\Users\Fahad.Rehman\Desktop\UW DataBootcamp\Machine_Learning_Supervised\Balanced_Random_Forest.PNG) 

Balanced Accuracy is 79%, precision is relatively higher than the above 4models but still at 0.04%. Precision of low_risk score is 100%



- **Easy Ensemble AdaBoost Classifier**

![](C:\Users\Fahad.Rehman\Desktop\UW DataBootcamp\Machine_Learning_Supervised\Easy_Ensemble_AdaBoost.PNG) 

Balanced Accuracy is 93%, precision is relatively higher than the above 5 models but overall low at 0.07% for high_risk score. Precision of low_risk score is 100% and recall is highest sitting at 94%



### **Summary:** 

In our first four models the accuracy_score is sitting at 65% or less which is not optimal, we prefer the score close to 100% for best fit. The balance Random Forest came as the second best with an accuracy of almost 79% and easy Ensemble AdaBoost has an accuracy of 94% and the highest recall of 95%. We would like to see the recall score close to 100% too. The SMOTE and UnderSampling results were the same to the last decimal point and needs to be investigate further.
