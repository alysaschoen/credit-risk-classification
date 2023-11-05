# Module 12 Report Template

## Overview of the Analysis
The primary objective of this analysis was to utilize logistic regression, a supervised machine learning technique, to predict whether a loan request is "healthy" or "high risk" based on specific features. These features include loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt,  all play a role in determining the loan's risk classification.


## Results

### Machine Learning Model 1: Original Dataset
  * Balanced accuracy score: 94%
  * Precision (Healthy): 100%
  * Precision (High-Risk): 87%
  * Recall (Healthy): 100%
  * Recall (High-Risk): 89%

### Machine Learning Model 2: Oversampled Dataset
  * Balanced accuracy score: 99%
  * Precision (Healthy): 100%
  * Precision (High-Risk): 87%
  * Recall (Healthy): 100%
  * Recall (High-Risk): 100%


## Summary
This model exhibits potential as a valuable tool for assessing loan risk, particularly if it allows for human review. It consistently attains high accuracy scores on both the original and oversampled datasets, with the oversampled dataset yielding a 5% accuracy rate increase. It excels in identifying healthy loan candidates and effectively recognizes high-risk candidates, signifying its reliability and practicality in the loan assessment process. Prioritizing the detection of high-risk loans is paramount in mitigating financial risks, making this model a valuable asset in risk assessment.




