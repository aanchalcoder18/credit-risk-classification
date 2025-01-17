# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  
Accuracy: 94%
HEALTHY LOANS
    Precision: 100%
    Recall: 100%
HIGH-RISK LOANS
    Precision: 87%
    Recall: 89%

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

Accuracy: 99% 
HEALTHY LOANS
    Precision: 100%
    Recall: 100%
HIGH-RISK LOANS
    Precision: 87%
    Recall: 100%
    
    
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

The accuracy levels for the Logisitcs Regression model did slightly better at 99% than the model using oversamplied data at 94%. The precision for both models were at 87% but the recall for the logisitics regression did much better at 100% rather than the 89% at the oversampled data for high-risk loans. For healthy loans the data was basically identical so, overall the logisitcs regression model did slightly better considering the accuracy level was almost 100%.