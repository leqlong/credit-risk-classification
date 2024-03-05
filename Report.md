# Module 20 Report

## Overview of the Analysis

The purpose of this analysis was to build machine learning models to predict credit risk based on financial information. The dataset provided contained various features related to borrowers' financial profiles, and the task was to predict the likelihood of a loan being healthy or high-risk.

The data included information such as loan amount, interest rate, employment length, debt-to-income ratio, and other relevant financial indicators. The target variable, loan_status, had two categories: '0' representing healthy loans and '1' representing high-risk loans.

## Results

* Machine Learning Model:
  * Balanced Accuracy Score: 0.952
  * Precision and Recall Scores:
	* Precision for healthy loans (0): 1.00
	* Recall for healthy loans (0): 0.99
	* Precision for high-risk loans (1): 0.85
	* Recall for high-risk loans (1): 0.91

## Summary

* Balanced Accuracy Score: The model achieved a high balanced accuracy score of 0.952, indicating excellent overall performance in predicting both healthy and high-risk loans.

* Precision and Recall Scores:
  * For healthy loans (0): The model achieved perfect precision (1.00) and very high recall (0.99), indicating that it effectively identified almost all healthy loans and rarely misclassified them.
  * For high-risk loans (1): The model achieved a precision of 0.85 and a recall of 0.91, indicating that while it accurately identified a high proportion of high-risk loans, there were some false positives (misclassifications of healthy loans as high-risk) but few false negatives (misclassifications of high-risk loans as healthy).

In summary, the machine learning model exhibits exceptional performance in predicting healthy loans, with near-perfect precision and recall. It also demonstrates strong performance in identifying high-risk loans, although there is a slightly higher false positive rate compared to false negatives.

Considering the critical nature of correctly identifying high-risk loans to mitigate potential financial losses, the model's high recall for high-risk loans is particularly important. Therefore, this model appears to be highly suitable for credit risk analysis tasks, providing reliable predictions with a balanced trade-off between precision and recall for both healthy and high-risk loans.