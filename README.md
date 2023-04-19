# Parameter Optimization of SVM
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)

All data is from one continuous EEG measurement with the Emotiv EEG Neuroheadset. The duration of the measurement was 117 seconds. The eye state was detected via a camera during the EEG measurement and added later manually to the file after analysing the video frames. '1' indicates the eye-closed and '0' the eye-open state. All values are in chronological order with the first measured value at the top of the data.


Number of Instances: 14980

Number of Attributes: 15

## Final Result Table

![image](https://user-images.githubusercontent.com/74672533/233187889-9c0fff68-1a19-4555-b458-0749af10c32f.png)


## Convergence Graph
![image](https://user-images.githubusercontent.com/74672533/233188106-8606f383-51c1-460f-9edc-3c755e38a913.png)


## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 5 has the best accuracy of 0.88 having kernel = rbf, Nu = 0.18 and Epsilon = 0.69.

## Written By
Name : Sidak Khotra
  
Roll No. : 102003649

Sub-Group: 3CO26
