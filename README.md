# Credit_Risk_Analysis

# Overview of the Loan Prediction Risk Analysis: 

We worked on real world challenge of credit risk. Credit risk has inherently unbalance classification problem. We will be using different techniques to train and evaluate models with unbalanced classes. We will be using imbalanced-learn and scikit-learn to build and evaluate models using resampling. Credit card dataset is used from Lending Club which provides lending services to the people. 
From oversample data used Random Over sampler and SMOTE algorithms, and from under sample used Cluster centroids algorithm. Combinational approach used over and under sampling SMOTEENN. 

Used Machine learning models that reduce bias: 

•	Balanced Random Forest Classifier 
•	Easy Ensemble Classifier. 

# Results:

## Balanced Accuracy scores of each algorithm used to test the data set:

![image](https://user-images.githubusercontent.com/75701769/116023396-0220da00-a61a-11eb-92c2-18c99c816cfc.png)

Naïve Random Oversampling:

=0.6603423204808787
=66% Accurate. 

SMOTE: 

=0.6537310478007576
=65% Accurate

Cluster Centroids:

=0.5442661782548694
=54% Accurate

SMOTEENN:

=0.6365938950069001
=64% Accurate

Balanced Random Forest Classifier 

=0.7885466545953005
=79% Accurate.

Easy Ensemble Classifier

=0.9154751595365336
=92% Accurate.

•	Naïve Random Oversampling: 

In this technical analysis, Precision for high-risk credit is 0.01 and low risk is 1.00. While the sensitivity for high-risk is 0.74 and low risk is 0.58. It is highly likely that the credit approval will be guaranteed to the low-risk category. Sensitivity shows that we know that the credit will be denied for high-risk percentage but how likely is it that it will be denied, it is 74% likely that it will detect it to be denied. Classification report is shown below: 

![Credit_Risk_Analysis](https://github.com/Zainak94/Credit_Risk_Analysis/blob/main/Resources/Naive_Random_Oversampling.PNG)

•	SMOTE:

In this technical analysis, Precision for high-risk credit is 0.01 and low risk is 1.00. While the sensitivity for high-risk is 0.62 and low risk is 0.68. It is highly likely that the credit approval will be guaranteed to the low-risk category, 68% guaranteed. Sensitivity shows that we know that the credit will be denied for high-risk percentage but how likely is it that it will be denied, it is 62% likely that it will detect it to be denied. Classification report is shown below: 


![Credit_Risk_Analysis](https://github.com/Zainak94/Credit_Risk_Analysis/blob/main/Resources/ SMOTE.PNG)

•	Cluster Centroids:

In this technical analysis, Precision for high-risk credit is 0.01 and low risk is 1.00. While the sensitivity for high-risk is 0.69 and low risk is 0.40. It is highly likely that the credit approval will be guaranteed to the low-risk category, 40% guaranteed. Sensitivity shows that we know that the credit will be denied for high-risk percentage but how likely is it that it will be denied, it is 69% likely that it will detect it to be denied. Classification report is shown below: 

![Credit_Risk_Analysis](https://github.com/Zainak94/Credit_Risk_Analysis/blob/main/Resources/ Cluster_Centroids.PNG)

•	SMOTEENN:

In this technical analysis, Precision for high-risk credit is 0.01 and low risk is 1.00. While the sensitivity for high-risk is 0.70 and low risk is 0.57. It is highly likely that the credit approval will be guaranteed to the low-risk category, 57% guaranteed. Sensitivity shows that we know that the credit will be denied for high-risk percentage but how likely is it that it will be denied, it is 70% likely that it will detect it to be denied. Classification report is shown below: 

![Credit_Risk_Analysis](https://github.com/Zainak94/Credit_Risk_Analysis/blob/main/Resources/ SMOTEENN.PNG)

•	Balanced Random Forest Classifier: 

In this technical analysis, Precision for high-risk credit is 0.03 and low risk is 1.00. While the sensitivity for high-risk is 0.70 and low risk is 0.87. It is highly likely that the credit approval will be guaranteed to the low-risk category, 87% guaranteed. Sensitivity shows that we know that the credit will be denied for high-risk percentage but how likely is it that it will be denied, it is 70% likely that it will detect it to be denied. Classification report is shown below: 

![Credit_Risk_Analysis](https://github.com/Zainak94/Credit_Risk_Analysis/blob/main/Resources/ Balanced_Random_Forest_Classifier.PNG)

•	Easy Ensemble Classifier:
In this technical analysis, Precision for high-risk credit is 0.05 and low risk is 1.00. While the sensitivity for high-risk is 0.93 and low risk is 0.90. It is highly likely that the credit approval will be guaranteed to the low-risk category, 90% guaranteed. Sensitivity shows that we know that the credit will be denied for high-risk percentage but how likely is it that it will be denied, it is 93% likely that it will detect it to be denied. Classification report is shown below: 

![Credit_Risk_Analysis](https://github.com/Zainak94/Credit_Risk_Analysis/blob/main/Resources/ Easy_Ensemble_Classifier.PNG)

# Summary:

Overall, we can see that the balance accuracy scores, and classification report shows how effective these machine learning models. Easy Ensemble Classifier is the most accurate out of all the models, it has 92% approx. accuracy. Precision is 5% for high risk and for low risk it is 100%. There is 93% guaranteed that the loan will be denied to high risk and 90% approval will be provided to the low-risk credit. The total is 99% and 90% accurate for both precision and sensitivity. 
From any of these models, easy ensemble classifier model will be highly likely to be used due to its accuracy. 
