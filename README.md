# Credit_Risk_Analysis
## Purpose
The purpose of this analysis was to create a supervised machine learning model that could accurately predict credit risk. In order to complete this task, we used 6 different methods, which are:

* Naive Random Oversampling
* SMOTE Oversampling
* Undersampling - Cluster Centroid 
* SMOTEENN Sampling - Combination of Under and Over Sampling
* Balanced Random Forest Classifying
* Easy Ensemble Classifying

Through each of these methods, I split my data into training and testing datasets, and compiled accuracy scores, confusion matries, and classification reports as my results.

## Results

#### 1: Naive Random Oversampling
Accuracy Score: 64.38% 

Precision High Risk: 1% 

Precision Low Risk: 100% 

Recall High Risk: 69% 

Recall Low Risk: 59%  

![image](https://user-images.githubusercontent.com/93050682/158742842-e97264fb-e133-49e9-be96-7bb00378908b.png)

#### 2: SMOTE Oversampling
Accuracy Score: 66.28%

Precision High Risk: 1%

Precision Low Risk: 100%

Recall High Risk: 63%

Recall Low Risk: 69%

![image](https://user-images.githubusercontent.com/93050682/158743000-df9c3c02-9fbf-4e70-b5b5-96c9b3b7a812.png)

#### 3: Undersampling - Cluster Centroid 
Accuracy Score: 54.42%

Precision High Risk: 1%

Precision Low Risk: 100%

Recall High Risk: 69%

Recall Low Risk: 40%

![image](https://user-images.githubusercontent.com/93050682/158743198-9a6050a2-7026-4d64-ad72-4d56310b8df7.png)

#### 4: SMOTEENN Sampling
Accuracy Score: 67.48%

Precision High Risk: 1%

Precision Low Risk: 100%

Recall High Risk: 76%

Recall Low Risk: 59%

![Smoteen Sampling](https://user-images.githubusercontent.com/93050682/158743507-add319fd-3d32-4036-940a-4102c6d0115b.PNG)

#### 5: Balanced Random Forest Classifying
Accuracy Score: 78.8%

Precision High Risk: 3%

Precision Low Risk: 100%

Recall High Risk: 70%

Recall Low Risk: 87%

![image](https://user-images.githubusercontent.com/93050682/158743989-32a66645-2d5e-4496-a774-3f61f9cc2eeb.png)

#### 6: Easy Ensemble Classifying
Accuracy Score: 93.16%

Precision High Risk: 9%

Precision Low Risk: 100%

Recall High Risk: 92%

Recall Low Risk: 94%

![image](https://user-images.githubusercontent.com/93050682/158744192-ab3cad9a-f74a-43ec-82dd-42f984a7fd38.png)

## Summary

In this analysis we are trying to find the best model that can detect if a loan is high risk or not. Becasue of that, we need to find a model that lets the least amount of high risk loans pass through as low risk. That correlating statistic for this is the recall rate for high risk and Accuracy score opf the model.
After factoring in main statistics like accuracy score , precison and recall rate , the model that I would recommend to use for predicting high risk loans is the Easy Ensemble Classifying model.


