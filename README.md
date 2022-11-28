# Credit Risk Analysis

## Objective

With credit risk you have the issues of having far more good loans when compared to risky loans. You then run into unbalanaced clasification problems when evaulating credit risk using large data sets. To prevent errors with credit risk we have been tasked to use two machine learning libraries that will review the data sets and use Supervised Machine Learning techniques to give data that can be used to predict the credit risk in the mortgage data set.

- Libraries Used
  - Imbalanced
  - Scikit
  
- Types of Machine Learning Techniques
  - Random Over Sampling
  - SMOTE
  - Cluster Centroids
  - SMOTEENN
  - Balanced Random Forest Classifer
  - Easy Ensemble Classifier
  
## Supervised Machine Learning Results

### Random Oversampling

1

- Balanced Accuracy Score: 64.1%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 60%-High_Risk and 68%-Low_Risk

### SMOTE
  
2

- Balanced Accuracy Score: 63.7%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 60%-High_Risk and 68%-Low_Risk

### Cluster Centroids

3

- Balanced Accuracy Score: 63.7%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 61%-High_Risk and 45%-Low_Risk

### SMOTEENN

4

- Balanced Accuracy Score: 52.9%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 70%-High_Risk and 57%-Low_Risk

### Balanced Random Forest Classifer

5

- Balanced Accuracy Score: 78.9%
- Precision Scores show that it is low for High_Risk (.03) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 70%-High_Risk and 87%-Low_Risk

### Easy Ensemble Classifier

6

- Balanced Accuracy Score: 93.2%
- Precision Scores show that it is low for High_Risk (.09) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 92%-High_Risk and 94%-Low_Risk

## Results

 Balanced Accuracy Ranged 
- 52.9% with SMOTEENN
- 93.2% with Easy Ensamble Classifier 

Generally the precisions scores remained for a majority of the techinques at 
- .01 for High_Risk
- 1.00 for Low_Risk 

The other ones were at .01 except for 
- .03 for Balanced Random Forest Classifer
- .09 for Easy Ensemble Classifer 

Recall rates varied for each group with the highest recall rate for 
- High_Risk with Easy Ensemble at 92% 
- Low_Risk was also the Easy Ensemble at 94%

After reviewing all of the methods above the Easy Ensemble Classifier gave the best results for all three catagories reviewed. 
- Balanced Accurary
- Precision 
- Recall

I would move forward with Easy Ensemble for future machine learning objectives. 