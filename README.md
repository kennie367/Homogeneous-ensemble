I have used the insurance and churn dataset to do a predictive analysis using the homogeneous ensemble.
In the insurance data set i have used a randomforestregressor since the target which is charges is continous and is  not a categorical data.
I have split the dataset into 80% training and 20% testing.
After creating the ensemble model the outcomes where as follows;
         R2 score: 0.8729071717985523
         MAE score: 2556.8669928847858
         MSE score: 19731000.359976657
In the insurance data set i have used a randomforestclassifier since the target which is exited is  categorical data.
I have split the dataset into 80% training and 20% testing.
After creating the ensemble model the accuracy of the model was;
         Accuracy: 0.854
         which means it is 85.4%
