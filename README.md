# **Credit-Risk-Analysis-and-Prediction**
Data Scientist Project Based Internship at ID/X Partners X Rakamin Academy
Created by Nova Zidane Ibrahim

## **Problem Statement**
Lending to applicants with Bad Risk is the biggest cause of financial loss. Credit losses are the amount of money lenders lose when applicants refuse to pay or run away with money they should have paid.

## **Objectives**
1. **Identify Patterns Indicating Bad Risk**

    The first objective is to recognize patterns in the data that indicate a person is less likely to be able to repay a loan or is considered a `"Bad Risk"`. This information will be used to take actions, such as rejecting the loan application, reducing the approved loan amount, or setting a higher interest rate, to compensate for the higher risk.

2. **Implementation of Machine Learning Algorithms to Build Predictive Models**

    The second objective is to apply machine learning algorithms to create predictive models. This model will allow the company to automatically predict whether the loan application submitted by the applicant will be labeled as a `"Bad Risk"` or not. With this, the company can approve or reject the loan application.

## **Result**
The Random Forest Model is the best model for predicting loan risk status among the various models evaluated. The Decision Tree Model also had high accuracy on the training data, but the Random Forest Model was better in terms of accuracy difference between training and testing data. The Random Forest Model showed better generalization ability compared to the XGBoost Model.
  - Random Forest Model: This model is considered the best for loan risk prediction due to its strong performance on both training and testing data.
  - Decision Tree Model: This model also shows high accuracy on training data, but may suffer from overfitting, as indicated by the larger accuracy difference between training and testing data.
  - XGBoost Model: While this model has high accuracy values, it does not perform as well as the Random Forest model, especially in terms of generalization on the test data.

## **Conclusion**
1. **Key Features**:The five most correlated features in determining the likelihood of loan repayment include `recoveries`, `collection_recovery_fee`, `total_resc_prncp`, `last_pymnt_d_year`, and `total_pymnt_inv`. The mentioned features are the most correlated in assessing loan repayment risk. This means that these factors strongly influence whether an applicant is likely to repay their loan or not.
2. **Risk Mitigation Strategies**: Recommended strategies for dealing with applicants who exhibit high-risk indicators. If an applicant has characteristics associated with a high risk of not repaying a loan, companies should consider actions such as rejecting their loan application, reducing the loan amount, or charging a higher interest rate. This strategy aims to reduce the overall financial risk for the company.

## **References**:
- https://www.investopedia.com/terms/g/grace_period.asp
- https://www.investopedia.com/terms/d/default2.asp
- https://www.valuepenguin.com/loans/what-does-it-mean-to-default-on-a-loan
- https://www.bankrate.com/personal-finance/debt/charged-off-as-bad-debt/#:~:text=If%20you've%20been%20delinquent,a%20loss%20for%20the%20company.
- https://www.investopedia.com/terms/c/chargeoff.asp
- https://github.com/fitria-dwi/Credit-Risk-Prediction
