# PROJECT TITLE - Loan Prediction Model


## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
This project aims to predict whether a loan application will be approved or rejected based on various features provided in the dataset. The dataset includes information about applicants' demographics, financial status, credit history, and other factors.

## DATA
The dataset was downloaded from Kaggle in csv and contains the following fields:
•	loan_id: Unique identifier for each loan application
•	gender: Gender of the applicant (Male/Female)
•	married: Marital status (Yes/No)
•	dependents: Number of dependents
•	education: Applicant's education level (Graduate/Not Graduate)
•	self_employed: Self-employment status (Yes/No)
•	applicant_income: Applicant's income in pounds
•	coapplicant_income: Co-applicant's income in pounds
•	loan_amount: Loan amount in thousands
•	loan_amount_term: Term of the loan in months
•	credit_history: Credit history (0 - No history, 1 - Has history)
•	property_area: Area type (Rural/Urban/Semiurban)
•	loan_status: Target variable (0 - Approved, 1 - Rejected)


## MODEL 
Model Selection: I used the following classification algorithms (e.g., Logistic Regression, Decision Trees, SVM, KNN) to find the best model to find the best model. 

## HYPERPARAMETER OPTIMSATION
I performed hyperparameter tuning for the Decision Tree classifier, I tuned the max depth amd the min samples split 


## RESULTS
A summary of your results and what you can learn from your model 


SVC Accuracy: 0.8018018018018018
              precision    recall  f1-score   support

           0       1.00      0.35      0.52        34
           1       0.78      1.00      0.88        77

    accuracy                           0.80       111
   macro avg       0.89      0.68      0.70       111
weighted avg       0.85      0.80      0.77       111


KNeighborsClassifier Accuracy: 0.7657657657657657
              precision    recall  f1-score   support

           0       0.72      0.38      0.50        34
           1       0.77      0.94      0.85        77

    accuracy                           0.77       111
   macro avg       0.75      0.66      0.67       111
weighted avg       0.76      0.77      0.74       111


Random Forest Classifer Accuracy: 0.7567567567567568
              precision    recall  f1-score   support

           0       0.68      0.38      0.49        34
           1       0.77      0.92      0.84        77

    accuracy                           0.76       111
   macro avg       0.73      0.65      0.67       111
weighted avg       0.74      0.76      0.73       111


You can include images of plots using the code below:
![Screenshot](image.png)



