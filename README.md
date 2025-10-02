**Loan Default Prediction**
**📌 Overview**

This project uses a Decision Tree Classifier to predict whether a loan applicant will default based on their financial and demographic data.

**📊 Dataset**

File: UpdatedLoanDefaults.csv ( in the repository )

Contains applicant info such as Age, Income, LoanAmount, CreditScore, EmploymentType, Education, MaritalStatus, LoanPurpose, etc.

Target column: Default (0 = No Default, 1 = Default).

All categorical features were converted to numeric values.

**⚙️ Model**

Algorithm: Decision Tree Classifier (scikit-learn)

**Steps:**

Load CSV → preprocess data

Train-test split (80/20)

Fit Decision Tree

Evaluate with accuracy score
