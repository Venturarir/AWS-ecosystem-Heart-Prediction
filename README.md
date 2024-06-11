# Final project for AWS class
## Problem description 
Predicting heart disease presents a critical challenge as it requires analyzing complex, multifaceted data to identify patterns associated with cardiovascular risk. 
Accurate prediction models can significantly improve early diagnosis and treatment, potentially saving lives by allowing for timely medical intervention. 
However, developing such models involves overcoming substantial hurdles in data collection, feature selection, and algorithmic design to ensure reliability and efficacy in diverse patient populations.
False negative (FN) predictions are especially dangerous in the world of medicine. 
## Solution overview
Amazon S3 buckets -> Data regarding patients medical records are collected and stored in S3 buckets. <br>
Data engineering -> Steps taken to adjust gender, remove missing values and normalise values. <br>
Model building -> Using AWS' XGBoost model as we are trying to predict a categorical value. <br>
Model evaluation -> Using metric AUC. See how the model has improved or worsened after new data input. <br>
Model deployment -> Not yet in use, as we could not get the function to work. <br>
Endpoint -> Keep the endpoint running or stop it according to business rules. <br>
