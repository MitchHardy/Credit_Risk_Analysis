# Credit_Risk_Analysis

## Overview of Project

### The purpose of this project is to accurately predict credit risk through supervised machine learning model and analysis. The methods that were used for this analysis are the folling; Naive Random Oversampling, SMOTE, Cluster Centroids, SMOTEENN, Balanced Random Forest Classifying, and Easy Ensemble Classifying. By using each of these methods I was able to predict credit card risk. 

## Results:
## Balanced Accuracy Scores:

### Naive Random Oversampling
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Accuracy%20Report.png) 

### SMOTE Oversampling
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Accuracy%20Report.png) 

### Cluster Centroids Undersampling
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/ClusterCentroid%20Accuracy%20Report.png) 

### SMOTEEN
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/SMOTEENN%20Accuracy%20Report.png) 

### Balanced Random Forest Classifying 
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/BRFC%20Classifier%20Accuracy%20Report.png) 

### Easy Ensemble Classifying
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20Classifier%20Accuracy%20Report.png)

## Precision & Recall Scores:

### Naive Random Oversampling
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Report.png) 

### SMOTE Oversampling
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Report.png) 

### Cluster Centroids Undersampling
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/ClusterCentroid%20Report.png) 

### SMOTEEN
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/SMOTEENN%20Report.png) 

### Balanced Random Forest Classifying 
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/BRFC%20Classifier%20Report.png) 

### Easy Ensemble Classifying
![This is an image](https://github.com/MitchHardy/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20Classifier%20Report.png) 

## Summary:
To review, I used six different machine learning models to predict credit card risk by detecting the amount of high risk loans. Below is an analysis of the six models and a recommendation for the most accurate model. 

First, we'll look at the top balanced accuracy scores. By looking at the numbers it's easy to see that the Easy Ensemble Classifying model scored higher than the rest of the models with an accuracy score of 93.2%. The next highest accuracy score came from the Balanced Random Forest Classifying model with a score of 78.8%. The rest had a relatively low accuracy score compared to the Easy Ensemble Classifying model. 

Next, we'll analyze the precision and recall scores. Specifically, I want to pay attention to the recall rates for high risk and low risk. Again, we are seeing the Easy Ensemble Classifying model outperform the rest of the models with a 92% high risk recall and a 94% low risk recall. The other models didn't even come close to these percentages with the exception of low risk recall frorm the Balanced Random Forest Classifying model. 

My recommendation to accurately predict credit risk would be using the Easy Ensemble Classifying model. This method is definitely the most effective of the six and will produce the most accurate credit card risk prediction. 
