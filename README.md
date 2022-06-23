# Credit_Risk_Analysis
Module17_Challenge
## Overview of the analysis: Explain the purpose of this analysis.
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I did oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then,I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. I evaluated the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results: 
Describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
#### Oversampling

The accuracy is 65%

![image](https://user-images.githubusercontent.com/100230706/175194073-c917543f-c998-4fe1-9c32-7d7eb086e121.png)

#### Smote Oversampling

The accuracy is 61%

![image](https://user-images.githubusercontent.com/100230706/175194180-a0669a62-d5e2-49bc-8815-a1db60e97efb.png)


#### Undersampling

The accuracy is 51%

![image](https://user-images.githubusercontent.com/100230706/175194251-79161463-843d-4b87-baa9-97d0f1fe0a7c.png)


#### Combination (Over and Under) Sampling

The accuracy is 63%

![image](https://user-images.githubusercontent.com/100230706/175194314-9de0f1f2-0889-4050-b115-dcf81609aaf6.png)


#### Balanced Random Forest Classifier

The accuracy is 78%

![image](https://user-images.githubusercontent.com/100230706/175194378-addf109b-756a-411a-881a-0ed52e2859fd.png)

#### Easy Ensemble AdaBoost Classifier

The accuracy is 93%

![image](https://user-images.githubusercontent.com/100230706/175194434-f0483f00-c44c-486e-964b-880c7d21c78e.png)




## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

As above pictures show, I did recommend to "Easy Ensemble AdaBoost Classifier" since the accuracy is higher than all other model and even in the report it shows all percentage is higher than 90%

![image](https://user-images.githubusercontent.com/100230706/175195961-470962f5-ac56-406f-9706-b8eb3faa5c20.png)

![image](https://user-images.githubusercontent.com/100230706/175195988-0e188420-ce42-4922-9d7c-b2bb81ec63a2.png)



