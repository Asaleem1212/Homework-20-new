# Module 12 Report Template

## Overview of the Analysis

The primary objective of this analysis was to apply machine learning techniques to predict credit risk. This entailed distinguishing between "healthy" loans (low risk) and "high-risk" loans using financial data. The dataset comprised various loan attributes, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and the loan status. The `loan_status` variable, which indicates whether a loan is considered "healthy" or "high-risk," was the target variable for our predictions.

The analysis involved several key steps, starting with data preprocessing to format the dataset correctly and splitting it into training and testing sets. The logistic regression model was then trained using the training dataset. The performance of this model was evaluated based on its ability to accurately predict the loan status on unseen testing data.

## Results

The results of the logistic regression model are as follows:

Machine Learning Model 1: Logistic Regression

- Accuracy Score: The model achieved an overall accuracy of 99%, indicating its strong performance in classifying loans correctly.

Precision Score:
- For healthy loans ('0'): The precision was 1.00, signifying that nearly all loans predicted as healthy were indeed healthy.
- For high-risk loans ('1'): The precision was 0.85, meaning that 15% of loans predicted as high-risk were actually healthy.

Recall Score:
- For healthy loans: The recall was 0.99, demonstrating the model's ability to identify 99% of all actual healthy loans.
- For high-risk loans: The recall was 0.95, showing the model's effectiveness in identifying 95% of all actual high-risk loans.

## Summary

The logistic regression model showcased remarkable efficiency in predicting loan risk, as evidenced by its high accuracy, precision, and recall scores. Its performance in identifying healthy loans is nearly flawless, making it an invaluable tool for financial institutions aiming to minimize the risk of loan defaults. Although the model's precision for high-risk loans is slightly lower, its high recall rate ensures that the majority of genuine risks are captured.

Given its overall performance, the logistic regression model is highly recommended for assessing loan risk. Its ability to accurately identify both healthy and high-risk loans can significantly enhance a company's loan approval process. However, considering the lower precision for high-risk loans, it may be beneficial to pair this model with additional risk assessment strategies to further reduce the occurrence of false positives. This dual approach could ensure a robust risk management framework, balancing the need for risk mitigation with the desire to support potential borrowers.