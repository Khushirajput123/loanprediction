# Loan Approval Prediction using Machine Learning
This project builds a **machine learning model to predict whether a loan application will be approved or rejected** based on applicant information such as income, education, credit history, and property area.
## Dataset Features
The dataset contains information about loan applicants and their financial details.
| Feature           | Description                                      |
| ----------------- | ------------------------------------------------ |
| Loan_ID           | Unique loan application ID                       |
| Gender            | Applicant gender                                 |
| Married           | Marital status                                   |
| Dependents        | Number of dependents                             |
| Education         | Education level                                  |
| Self_Employed     | Whether the applicant is self-employed           |
| ApplicantIncome   | Income of the applicant                          |
| CoapplicantIncome | Income of the co-applicant                       |
| LoanAmount        | Loan amount requested                            |
| Loan_Amount_Term  | Loan repayment term                              |
| Credit_History    | Applicant credit history                         |
| Property_Area     | Property location (Urban/Rural/Semiurban)        |
| Loan_Status       | Target variable (Y = Approved, N = Not Approved) |
---
## Project Workflow
1. Load and explore the dataset
2. Handle missing values
3. Convert categorical variables into numerical form
4. Split the dataset into training and testing data
5. Train a **Support Vector Machine (SVM) model**
6. Evaluate model performance using accuracy score


## Model Used

### Support Vector Machine (SVM)
SVM is a supervised machine learning algorithm used for **classification problems**. It works by finding the **best boundary that separates approved and rejected loan applications** based on applicant features.
## Model Performance

* **Training Accuracy:** 0.765
* **Testing Accuracy:** 0.689
The model learns patterns from the training data and predicts loan approval on unseen test data.
## Tools and Libraries
* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
## Objective
The goal of this project is to demonstrate a **machine learning pipeline for loan approval prediction**, including data preprocessing, feature scaling, model training, and evaluation.




