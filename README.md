# credit-risk-classification
## Module 20 Challenge  

## Purpose of the Analysis
This analysis evaluates the performance of a logistic regression model in predicting whether a loan is a **healthy loan (0)** or a **high-risk loan (1)**. The goal is to assess how effectively the model can differentiate between these two categories using metrics such as **accuracy**, **precision**, and **recall**.

## Performance Metrics
- **Accuracy**: 99% – The model correctly predicts the loan status 99% of the time.
- **Healthy Loan (0):**
  - **Precision**: 1.00 – All loans predicted as healthy were indeed healthy.
  - **Recall**: 0.99 – Almost all healthy loans were correctly identified.
- **High-Risk Loan (1):**
  - **Precision**: 0.84 – Some healthy loans were incorrectly predicted as high-risk.
  - **Recall**: 0.94 – The model identified 94% of the high-risk loans correctly.

## Summary and Recommendation
The logistic regression model performs very well in predicting **healthy loans** with near-perfect precision and recall. However, it shows slightly weaker performance when identifying **high-risk loans**, with 107 false positives (healthy loans predicted as high-risk) and 37 false negatives (high-risk loans predicted as healthy).

Given the high overall accuracy and strong performance in predicting healthy loans, this model is **recommended** for use by the company. However, it is suggested that further tuning or alternative models be considered to reduce false positives and improve precision for high-risk loans. This will enhance the model's reliability, especially when identifying risky borrowers.

## Resources
UCB Starter Files, troubleshooting with GitHub CoPilot inside Visual Studio Code.