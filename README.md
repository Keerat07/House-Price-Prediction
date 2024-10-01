# House-Price-Prediction
Using linear regression as well as random forest and achieving r2 score of 0.82

As we got the dataset from kaggle and further we started with finding out the missing elements
In our dataset the models were less than 5% of the data so we removed them 
This follows Complete Case Analysis 
further we applied scaling to the dataset the scaling we use was mean normalization and to categorical data we applied one hot encoding to remove the string values
this was done using pipeline as while training the pipeline and the data will be sent first it will be scaled and then linear regression will be applied to it
which got us the r2 score of 0.648824239353417  and MSE is 4802392014.520186
And then further we thought to apply randomForestRegressor which increased the r2 score value by 18% and reduce MSE by more than half
