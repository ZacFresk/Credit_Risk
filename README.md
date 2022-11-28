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

![1](https://user-images.githubusercontent.com/107363203/204202434-5f03a1a4-d5d6-49d2-8f88-6d294ff7a750.png)


- Balanced Accuracy Score: 64.1%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 60%-High_Risk and 68%-Low_Risk

### SMOTE
  
![2](https://user-images.githubusercontent.com/107363203/204202444-aaa890b0-a165-4bb8-91f2-0a8f6b8f07f6.png)


- Balanced Accuracy Score: 63.7%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 60%-High_Risk and 68%-Low_Risk

### Cluster Centroids

![3](https://user-images.githubusercontent.com/107363203/204202468-e679c54a-27ac-4e01-9ee5-ec74fd8e8f18.png)


- Balanced Accuracy Score: 63.7%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 61%-High_Risk and 45%-Low_Risk

### SMOTEENN

![4](https://user-images.githubusercontent.com/107363203/204202478-7adc56bd-56ba-48bf-91cd-f1bc635ea614.png)


- Balanced Accuracy Score: 52.9%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 70%-High_Risk and 57%-Low_Risk

### Balanced Random Forest Classifer

![5](https://user-images.githubusercontent.com/107363203/204202486-9d3090ce-3045-4a6b-970c-e0e8e5af779f.png)


- Balanced Accuracy Score: 78.9%
- Precision Scores show that it is low for High_Risk (.03) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 70%-High_Risk and 87%-Low_Risk

### Easy Ensemble Classifier

![6](https://user-images.githubusercontent.com/107363203/204202495-6c3c321f-b36d-4249-a517-8c0d870e15e5.png)


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
