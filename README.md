# Credit_Risk_Analysis
## Overview
Use a credit card credit dataset from LendingClub (a peer-to-peer lending services company) to oversample the data and compare two new machine learning models to evaluate the performance of these models on whether they should be used to predict credit risk.

## Results
The random over sampler model showed an accuracy score of 65%.
The high risk precision is 1%  with 62% sensitivity.  The low risk population precision is 100% with a sensitivity of 68%. 

The smote model showed an accuracy score of 64%.
The high risk precision is 1% with 63% sensitivity.  The low risk population precision is 100% with a sensitivity of 66%. 

The cluster centroids model showed an accuracy score of 52%.
The high risk precision is 1% with 63% sensitivity.  The low risk population precision is 100% with a sensitivity of 40%. 

The smoteenn model showed an accuracy score of 62%.
The high risk precision is 1% with 68% sensitivity.  The low risk population precision is 100% with a sensitivity of 57%. 

The balanced random forest classfier model showed an accuracy score of 79%.
The high risk precision is 4% with 67% sensitivity.  The low risk population precision is 100% with a sensitivity of 91%. 

The easy ensemble  classifier model showed an accuracy score of 93%.
The high risk precision is 7% with 91% sensitivity.  The low risk population precision is 100% with a sensitivity of 94%. 
