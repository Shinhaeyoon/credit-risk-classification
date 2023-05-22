# Module 12 Report

## Overview of the Analysis

Two logistic regression models were compared to predict loan status. The second model, trained with balanced data (56271 each) using random oversampling, showed improved accuracy, recall, and F1 score compared to the first model trained on imbalanced data (0;56271, 1;1881). However, there was a slight decrease in precision for predicting high-risk loans in the second model, possibly due to overfitting. Despite this, the overall performance of the second model warrants its use due to higher scores and accuracy.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  - Balanced Accuracy score: 0.9520479254722232
  - Precision: 1.00 for predicting healthy loans, 0.85 for predicting high-risk loans
  - Recall: 0.99 for predicting healthy loans, 0.91 for predicting high-risk loans


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  - Balanced Accuracy score: 0.9936781215845847
  - Precision: 1.00 for predicting healthy loans, 0.84 for predicting high-risk loans
  - Recall: 0.99 for predicting healthy loans, 0.99 for predicting high-risk loans


## Summary
Two logistic regression models were utilized to predict loan status based on various variables. The first model was trained on a dataset with a significant imbalance in the number of instances between the two loan statuses. In contrast, the second model was trained on a dataset with an equal number of instances for each loan status, achieved through random oversampling.

The use of random oversampling resulted in improvements in accuracy and recall. Recall measures the model's ability to correctly identify all relevant instances of a specific class. However, there was a slight decrease in precision when predicting high-risk loans. Precision indicates the proportion of instances predicted as a certain class that are actually correct. This decrease in precision may be attributed to the random oversampling technique, which could potentially induce overfitting.

The F1 score, which combines precision and recall into a single measure, was higher in the second model. The F1 score provides a balanced assessment of both metrics and is considered a valuable metric for evaluating model performance.

Although the precision of predicting high-risk loans decreased slightly in the second model, it is still worthwhile to utilize this model due to its overall higher score and accuracy.
