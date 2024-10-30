The project aimed to **predict loan defaults** using logistic regression model. Key aspects of the project include:

**Data Collection:**

Data was obtained from Freddie Mac’s Single Family Home Loan dataset, with information on mortgage characteristics (loan amount, interest rate, etc.) and borrower demographics (credit score, income, etc.). The target variable was "Delinquent," which indicated whether a borrower defaulted on a loan.

**Data Preprocessing:**

Missing values were handled using median imputation.
SMOTE (Synthetic Minority Oversampling Technique) was applied to address the class imbalance in the "Delinquent" variable.
Categorical variables were transformed using one-hot encoding to ensure compatibility with the model.

**Exploratory Data Analysis (EDA):**

Outlier detection and analysis of key variables, like credit score and prepayment behavior, which showed correlations with loan default likelihood.
Key features such as Credit Score, Mortgage Insurance Percentage, and Loan-to-Value Ratio were identified as influential for default prediction.

**Feature Selection:**

Backward Elimination Technique was applied for feature selection, highlighting critical features like Credit Score, Original UPB, Debt-to-Income Ratio, and Interest Rate.

**Model Building and Evaluation:**

Logistic Regression models was trained to predict loan defaults.
Evaluation metrics included precision, recall, F1 score, and AUC-ROC score.

**Model Validation:**

Additional validation and evaluation steps, such as using a confusion matrix, were employed to further understand model performance, especially the rate of false positives and false negatives.

The project demonstrated that Logistic Regression effectively handles large datasets and complex relationships, making it suitable for predicting loan defaults.
