# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis. We are trying to predict the loan_status using other indicators
* Explain what financial information the data was on, and what you needed to predict. The indicators where: loan_size	interest_rate	borrower_income	debt_to_income	num_of_accounts	derogatory_marks	total_debt
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).I wanted to predict if the client had an active loan status or if they didnt and we saw this by either having a 0 or 1
* Describe the stages of the machine learning process you went through as part of this analysis. We did an anlysis based on the models to better fit the data in order to predict the clients loan status 
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method). The way we fitted data was to use logisticregression however do to some complications we had on fitting the data we also needed to use resampling method in order to better have a better anaylsis

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  Model 1 accuracy is 0.9520479254722232
  Model 1 precision is 1 for "0" and 0.85 for "1"
  Model 1 Recall is 0.99 for "0" and 0.91 for "1"



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  Model 2 accuracy is 0.9936781215845847
  Model 2 precision is 1 for "0" and 0.84 for "1"
  Model 2 Recall is 0.99 for "0" and 0.99 for "1"

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best? 
Model 2 seems to perform better because it has adjusted the data and it has improved the overall accuracy of the model. Furthermore, recall has also improved but precision did decrease a little bit. Nonetheless, the huge improvement that accuracy had makes the model way more attractive than model 1. 
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) 
There is a little bit of difference when comparing the models for trying to predit the "1"'s as the recall largely improves but the precision did dimish a lot. Thus, I do not believe that performance affects the problem we are trying to solve. In terms of improving precision or recall than the models might be different nonetheless for 1 and 0 there isnt that much of a difference. 

If you do not recommend any of the models, please justify your reasoning.
