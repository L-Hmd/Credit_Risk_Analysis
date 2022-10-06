# Credit_Risk_Analysis
### Overview
In this project, we analyzed the credit risk using the imbalanced-learn and scikit-learn on the sample credit card dataset from LendingClub, a peer-to-peer lending service company. The following six machine-learning modles were run and evaluated for performance and accuracy in predicting credit risk:
* RandomOverSampler
* SMOTE
* ClusterCentroids
* SMOTEENN
* BalancedRandomForestClassifier
* EasyEnsembleClassifier

### Results
The results are presented in the order of the best-performing models to the worst based on their balanced accuracy score. 
#### 1) EasyEnsembleClassifier 
* Balanced Accuracy Score: 93.2%
* Precision: high risk 9%, low risk 100%
* Recall: high risk 92%, low risk 94%

![image](https://user-images.githubusercontent.com/100629325/194392689-2ddda59d-f7a4-429c-bdeb-a3c853dd37c5.png)

![image](https://user-images.githubusercontent.com/100629325/194392986-fee7ed66-5e5b-4173-88cf-ebef5ef4b6c7.png)

#### 2) BalancedRandomForestClassifier
* Balanced Accuracy Score: 78.9%
* Precision: high risk 3%, low risk 100%
* Recall: high risk 70%, low risk 87%

![image](https://user-images.githubusercontent.com/100629325/194394853-a62b2645-c1b3-42e9-a45c-c14d31e6b08d.png)

![image](https://user-images.githubusercontent.com/100629325/194394897-ed32c10d-9024-4ce0-aaf2-1263331ba58e.png)

#### 3) RandomOverSampler
* Balanced Accuracy Score: 64.7%
* Precision: high risk 1%, low risk 100%
* Recall: high risk 62%, low risk 67%

![image](https://user-images.githubusercontent.com/100629325/194397321-8e984e87-3355-4d14-8f3c-bd7e73fb1bc4.png)

![image](https://user-images.githubusercontent.com/100629325/194397372-edcd6157-1b24-4789-9a48-702d8d661527.png)

#### 4) SMOTEENN Combination (Over and Under) Sampling
* Balanced Accuracy Score: 64.2%
* Precision: high risk 1%, low risk 100%
* Recall: high risk 70%, low risk 58%

![image](https://user-images.githubusercontent.com/100629325/194397642-4ec96df3-647f-4c7f-97ca-e6a57f907b0d.png)

![image](https://user-images.githubusercontent.com/100629325/194397687-aec458f8-35aa-4178-a613-0466c1f74b29.png)

#### 5) SMOTE Oversampling
* Balanced Accuracy Score: 62.5%
* Precision: high risk 1%, low risk 100%
* Recall: high risk 62%, low risk 63%

![image](https://user-images.githubusercontent.com/100629325/194398254-2942bda0-fe6b-4167-8679-35dba8eafe96.png)

![image](https://user-images.githubusercontent.com/100629325/194398283-67f97d8d-2e0d-4363-b30b-69c2cc738ecf.png)

#### 6) Cluster Centroids Undersampling
* Balanced Accuracy Score: 51.8%
* Precision: high risk 1%, low risk 100%
* Recall: high risk 57%, low risk 46%

![image](https://user-images.githubusercontent.com/100629325/194399041-9bdc583d-97df-4ed2-8196-7f009d18dbeb.png)

![image](https://user-images.githubusercontent.com/100629325/194399064-7e1b4cfc-9176-4ca5-a781-2e4ed9af0dcd.png)
