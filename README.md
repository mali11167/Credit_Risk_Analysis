# Credit_Risk_Analysis
## Overview
In this project we doing credit risl analysis. Credit risk is a very unbalanced classification problem and good loans are easily affected by risky
loans. In this project we will be using different techniques to train and train and evaluate models to see the accuracy level and to evaluate models
with unbalanced classes.
## Results
We applied six machine learning models on the credit risk data. Our results are as follows:
* First model was ensemble learning model and in this we applied the random forest classifier and easy ensemble classifier. Our result with random forest was:
![random](https://user-images.githubusercontent.com/91965321/154777044-e7909743-44b8-4463-bf42-a41e849fd031.PNG)
Balance accuracy score is 0.78 which is 78%
* Second we used the easy ensemble classifier
![easy](https://user-images.githubusercontent.com/91965321/154777170-704abe9c-2580-472a-ab1c-5074c1fc6df2.PNG)
We see the balance accuracy score in this is 0.92 which is 92%.
These both models have weak algorithm trees and tha's why in the result we see high false positives
* Third we used Naive Random Oversampling and the results were:
![oversampling](https://user-images.githubusercontent.com/91965321/154777339-6cde91cd-23c6-4e56-b5ab-8956c353948d.PNG)
We see the accuracy in this model is 0.65 which is only 65%
* Fourth we used the SMOTE Oversampling and the results were:
![smote](https://user-images.githubusercontent.com/91965321/154777475-67a925bf-22bc-4694-8dd6-97fcb8287e58.PNG)
We see the accuracy level on this model is 0.62 which is 62%. We also see that the random oversampling and smote doesn't have much of a difference 
when it comes to the accuracy level. 
* Fifth we used ClusterCentroids resampler and the results were:
![cluster](https://user-images.githubusercontent.com/91965321/154777809-b5a5c6bd-c880-489b-a872-275afa462c4d.PNG)
We see the accuracy level on this is 52% and recall is 59%
* Last model we used was SMOTEENN and the results were:
![smotten](https://user-images.githubusercontent.com/91965321/154778237-143d2a62-bdaf-41ce-b769-ed8cc653151a.PNG)
We see the accuracy level in this models is 51% and recall is 70%

## Summary
With the analysis of all the six machine learning models I think the best model to use will be Smoteenn. As we from the results that this model has the highest
number of recalls which means that the measure of our model correctly identifying True Positives is higher. With this model we will be able to correctly and closely 
identify the credit risk which would reduce the error of outnumbering the risky loans and properly identifying the qualifying loans. 




