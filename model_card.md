# Model Card

This project aims to predict whether a loan application will be approved or rejected based on various features provided in the dataset. The dataset includes information about applicants' demographics, financial status, credit history, and other factors.

## Model Description

**Input:** The dataset was downloaded from Kaggle in csv and contains the following fields:
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


**Output:** 
Model Selection: Different classification algorithms (e.g., Logistic Regression, Decision Trees, SVM, KNN) to find the best model.
Model Deployment: The best-performing model was deployed for future loan approval predictions.


**Model Architecture:** 
Modelling: Model using loan_amount and loan_status, test size = 0.3, logistic regression model instantiated. 
Feature engineering convert categorical features to binary, logistic regression model instantiated again. The most important features were displayed on a bar plot. 
Decision tree classifier: Instantiate a Decision Tree classifier and hyperparameter tuning performed.
Data Preprocessing: Handling missing values, encoding categorical variables, scaling numerical features, and splitting the data.
Model Selection: Different classification algorithms (e.g., Logistic Regression, Decision Trees, SVM, KNN) to find the best model.
Training and Evaluation: Training the selected model(s) on the training set, making predictions on the test set, and evaluating performance using metrics like accuracy, precision, recall, and F1-score.
Model Deployment: The best-performing model was deployed for future loan approval predictions.

## Performance

Model Performance: Detailed analysis and performance metrics of different models tested on the dataset.
Insights: Insights derived from the analysis that can be helpful for loan approval decision-making.


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

## Limitations
This project explores various machine learning models to predict loan approval or rejection based on applicant information. It provides a framework for understanding how different factors influence loan approval decisions.
Hyperparameter tuning was only performed on the Decision tree classifier, further investigation would be required on other classification models explored in this example. 
Decision tree classifier: Instantiate a Decision Tree classifier and hyperparameter tuning performed.
Further classifications models including deep learning, could be explored for a higher accuracy. 

## Trade-offs

Outline any trade-offs of your model, such as any circumstances where the model exhibits performance issues. 
