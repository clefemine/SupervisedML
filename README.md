# Supervised Machine Learning Project

## Credit Risk Analysis

### Project Overview

By implementing machine learning models using imbalanced-learn and scikit-learn libraries. Resampling techniques will address the class imbalance so a credit risk prediction can be made to evaluate the performance of models with unbalanced classes. A recommendation will made based on the results collected from the models.
 
 ### Resources
 
 Data Source: LoanStats_2019Q1.csv
 
 Software: Python 3.7.6, Jupyter Notebook 6.1.3
 
 ### Summary
 
 Oversample:
 - RandomOverSample algorithm: From the confusion matrix results, the precision for the high credit risk is extremely low, indicating a large number of false positives, which indicates an unreliable positive classification. The recall score is high for the high credit risk applications, which is indicative of a small number of false negatives.In summary, this RandomOverSample model is fairly good at classifying high credit risk loans because the model’s accuracy, 0.641.
 
 - SMOTE algorithm: From the confusion matrix results, the precision for the high credit risk is extremely low, indicating a large number of false positives, which indicates an unreliable positive classification. The recall score is high for the high credit risk applications, which is indicative of a small number of false negatives. In summary, this SMOTE model is moderately good at classifying high credit risk loans because the model’s accuracy, 0.651.
 
 Undersample:
 - Cluster centroids algorithm: From the confusion matrix results, the precision for the high credit risk is extremely low, indicating a large number of false positives, which indicates an unreliable positive classification. The recall score is high for the high credit risk applications, which is indicative of a small number of false negatives. In summary, this cluster centroids model is moderately good at classifying high credit risk loans because the model’s accuracy, 0.651.
 
 Combination:
 - SMOTEENN algorith: From the confusion matrix results, the precision for the high credit risk is extremely low, indicating a large number of false positives, which indicates an unreliable positive classification. The recall score is high for the high credit risk applications, which is indicative of a small number of false negatives. In summary, this SMOTEENN model is not good at classifying high credit risk loans because the model’s accuracy, 0.548.

 ### Results

Based on the model results the SMOTE algorithm model is recommended because of the high accuracy score and symmetrical recall (sensitivity) score. This shows more reliability in the results of the predictions. Combining models would be ideal but out of the models used in this project SMOTE will yield the most accurate results. 
