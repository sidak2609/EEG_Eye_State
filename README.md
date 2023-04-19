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

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of Instances: 14980

Number of Attributes: 15

## Final Result Table

| Sample | Best Accuracy | Best Kernel |	Best Nu |	Best Epsilon |
| 0 |	1	| 0.54 |	sigmoid |	5.90 |	1.90 |
| 1	| 2	| 0.56 | rbf | 4.71	| 0.52 | 
| 2	| 3	| 0.55 | linear	| 1.19	| 0.14 | 
| 3	| 4	| 0.55 | sigmoid	| 7.24	| 3.44 | 
| 4	| 5	| 0.88 | rbf	| 0.18	| 0.69 | 
| 5	| 6	| 0.55 | sigmoid	| 9.59	| 0.65 | 
| 6	| 7	| 0.53 | linear	| 0.43	| 3.08 | 
| 7	| 8	| 0.54 | rbf	| 2.61	| 3.11 | 
| 8	| 9	| 0.54 | linear	| 7.76	| 0.62 | 
| 9	| 10| 0.56 | sigmoid	| 0.56	| 3.40|  

## Convergence Graph
![graph](https://user-images.githubusercontent.com/72306997/233000047-3bbc6cf2-8ec0-4276-8519-17da7da2fb25.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.97 having kernel = Poly, Nu = 1.27 and Epsilon = 6.87.

## Written By
Name : Sidak Khotra
  
Roll No. : 102003649

Sub-Group: 3CO26
