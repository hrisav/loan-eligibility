# loan-eligibility

Problem Statement
-

Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban, and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan. Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.

Variable Description
-

Loan_ID, Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area, Loan_Status

Train data: 614, 13

Findings:
-

- Missing values were imputed.
- EDA was performed to find out the key features on which Loan_Status is dependent.
- Encoding was done on categorical variables.
- Accuracy was found out in case of KNN, Decision Tree, Logistic Regression (along with Cross Validation and Hyperparameter Tuning)
