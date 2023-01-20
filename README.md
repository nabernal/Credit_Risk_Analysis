# Credit Risk Analysis

## Overview of the loan prediction risk analysis:

#### Supervised machine learning is used to classify data or predict outcomes by creating models using real data. This branch of machine learning relies on data with features or input and targets, also known as outputs. For example, supervised learning can be implemented by credit card companies to predict credit risk, which can help determine whether a credit card application will be approved or denied. A total of six models were created using different sampling methods. Then, the accuracy of each model was assessed to find a potential model that can predict credit risk. 


## Results:

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

1. Naive Random Oversampling
- Balanced accuracy score: 65%
- High Risk Precision Score: 1%
- High Risk Recall Score: 72%
- Low Risk Precision Score: 100%
- Low Risk Recall Score: 57%
 With 1% precision, 72% recall and balanced accuracy score of 65% this model is not reliable at accuratly classifying high credit risk.
 
2. SMOTE Oversampling
- Balanced accuracy score: 66%
- High Risk Precision Score: 1%
- High Risk Recall Score: 63%
- Low Risk Precision Score: 100%
- Low Risk Recall Score: 69%
 
 With 1% precision, 63% recall and balanced accuracy score of 66% this model is not reliable at accuratly classifying high credit risk.
 
3. Undersampling:
- Balanced accuracy score: 54%
- High Risk Precision Score: 1%
- High Risk Recall Score: 69%
- Low Risk Precision Score: 100%
- Low Risk Recall Score: 40%
  
  With 1% precision, 69% recall and balanced accuracy score of 54% this model is not reliable at accuratly classifying high credit risk.
 
4. Combination (Over and Under) Sampling:
- Balanced accuracy score: 65%
- High Risk Precision Score: 1%
- High Risk Recall Score: 72%
- Low Risk Precision Score: 100%
- Low Risk Recall Score: 57%
  
  With 1% precision, 72% recall and balanced accuracy score of 65% this model is not reliable at accuratly classifying high credit risk.
 
5.Balanced Random Forest Classifier
- Balanced accuracy score: 78%
- High Risk Precision Score: 4%
- High Risk Recall Score: 64%
- Low Risk Precision Score: 100%
- Low Risk Recall Score: 91%

 With 4% precision, 64% recall and balanced accuracy score of 78% this model is not reliable at accuratly classifying high credit risk.
 
6. Easy Ensemble AdaBoost Classifier
- Balanced accuracy score: 93%
- High Risk Precision Score: 7%
- High Risk Recall Score: 92%
- Low Risk Precision Score: 100%
- Low Risk Recall Score: 93%
 With a 92% recall and balanced accuracy score of 93% this model seems like it like a good candidate but the low precision score of 7% shows it is still not a good model for identifying high credit risk.
 
## Summary:

There is a summary of the results (2 pt)
Both Oversampling models did not perform well, but the Naive Random Oversampling model performed slightly better than the SMOTE Oversampling model. Naive Random Oversampling model also performed better than the undersampling model. The oversampling and Naive Random Oversampling models performed similarly. The Ensemble models performed better than the resampling models. The Easy Ensemble model is the better of the two ensemble models. 

Suggestion: Although Easy Ensemble was the best model in this round of testing, it still had a low precision score (7%) like all the other models. Therefore this is not a good model with a low accuracy at predicting high credit risk and high accuracy at falsely predicting high credit risk. Further modifications are required to develop a good model that can predict high credit-risk credit card applicants. 

