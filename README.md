# Credit_Risk_Analysis
## Overview of the Analysis 
### The purpose of this repository is to run six machine learning modules to look at the different balanced accuracy and the precision and recall scores of all six machine learning modules. 
## Results
* ### Random Over Sampler Model
For the Random Over Sample Model, the accuracy is 0.65 with a precision for high risk at 0.01 and a precision for low risk at 1.00. A huge discrepancy amongst the two values. However, the recall scores for high risk and low risk are similar at 0.68 and 0.61. 
<img width="754" alt="Screen Shot 2022-06-19 at 2 16 44 PM" src="https://user-images.githubusercontent.com/100246124/174495492-d0655640-fa1a-4bb3-a7ea-291583ab657c.png">


* ### SMOTE Oversampling Model
For the SMOTE Oversampling Model, the accuracy score is 0.62. Similarly to the random over sampler method, the precision for high risk is at 0.01 and 1.00 for low risk. The recall scores for high risk is at 0.61 and very similar for low risk at 0.64. 
<img width="739" alt="Screen Shot 2022-06-19 at 2 23 46 PM" src="https://user-images.githubusercontent.com/100246124/174495513-aff0f432-c4ea-4dae-bd9d-4b869e31055d.png">


* ### Cluster centroids Model
For the Cluster Centroids Model, the accuracy score is 0.51. The precision score for high risk is 0.01 and 1.00 for low risk. While the recall score for high risk is 0.60 and low risk 0.43. 
<img width="726" alt="Screen Shot 2022-06-19 at 2 26 21 PM" src="https://user-images.githubusercontent.com/100246124/174495520-9b58f56e-258d-4c1a-962f-5503fdb68510.png">


* ### SMOTENN Model 
  The SMOTENN Method has an accuracy score of 0.64. A precision score of 0.01 for high risk and 1.00 for low risk. The recall scores are .70 for high risk and 0.58 for low risk. 
<img width="705" alt="Screen Shot 2022-06-19 at 2 28 59 PM" src="https://user-images.githubusercontent.com/100246124/174495529-b7a54c11-f8e2-431f-954c-0f731785813b.png">

* ### Balanced Random Forest Classifier Model
The Balanced Accuracy score for this Model is 0.79. The precision score for high risk is 0.04 while the precision score for high risk is 1.00. The recall score for high risk is 0.67 with a low risk recall score of 0.91. 
<img width="777" alt="Screen Shot 2022-06-19 at 2 39 25 PM" src="https://user-images.githubusercontent.com/100246124/174496133-4c80f647-2b86-422a-af6d-c3cdeb268ee4.png">

* ### Easy Ensemble Classifier 
The accuracy score for this model is 0.93 with a precision score of 0.07 for high risk and 1.00 for low risk. The recall score is 0.91 for high risk and 0.94 for low risk. 
<img width="768" alt="Screen Shot 2022-06-19 at 2 38 57 PM" src="https://user-images.githubusercontent.com/100246124/174496126-ebfc78ee-7543-4c73-aceb-dfddd709fd26.png">
## Summary 
Amongst the 6 models, the first 4 models had a similar accuracy score between 0.53-0.65. However, when we begin looking at the balanced random forest classifier score we begin to see a big jump at the accuracy score at 0.79. With the easy ensemble classifier, we have an accuracy score of 0.93. Another thing to note is the precision scores, the module with the best precision score for high risk is the easy ensemble classifier. When looking at the recall scores, again we see that the easy ensemble classifier with the best recall scores at 0.91 and 0.94 for high risk and low risk, respectably. 

After analyzing all six marching learning models, the best model to use is the Easy Ensemble Classifier with the highest accuracy score, precision score and recall score. The model that I would least recommend would be the Cluster Centroids Model as it has an accuracy score of 0.51 and a recall score for high risk at 0.60 and a recall score of 0.43 for low risk. Out of all six learning machine learning models, it is the least accurate. 
