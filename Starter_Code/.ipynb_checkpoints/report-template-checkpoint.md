# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis was to identify healthy and risky loans. The lending data of users was used to perform the analysis, which included a wide range of data points like debt to income ratio and borrower income. 

In this analysis, we were tring to predict the loan status, with binary result values of either 0 (Healthy Loan) or 1 (High-Risk Loan). As part of this analysis, we stared with splitting the data into training and testing data, and then conducted a logistic regression analysis. 

A second iteraton of the logistic regression analysis was conducted with resampled training data, instead of the original data. 


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * The first machine learning model has both a high precision and recall for both "0" and "1", so it predicted well. The preciosn and recall for "0" is almost 100%, where as "1" has a fairly high precision and recall of 0.87 and 0.89, respectively. The model has a high accuracy of 0.99 as well.  
  
  
  
* Machine Learning Model 2:
  * In the second machine learning model, the "0" loans still have a high precision and recall of 100%. The "1" loan's precision is still the same at 0.87; however, the recall has increased from 0.89 to 0.93. Therefore, the model is a better fit for the oversampled data and has a better predicitive ability. The model has a accuracy of 1.00. The model performs better, or just as well as, than the first model with respect to all the metrics. 

## Summary

The second model should be used since it has a better recall and accuracy than the first model. More importantly, the model has a much better recall for risky loans. Risky loans pose a much greater risk since they pose the possibility of a higher financial loss, so the second model should be preferred.  
