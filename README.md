# 🏦 Loan Approval Prediction

This is my MSc Statistics final semester project focused on predicting loan approval status based on various applicant features. The project uses machine learning models to automate the decision-making process for financial institutions.

## 📌 Project Overview

The goal of this project is to build a classification model that predicts whether a loan application will be approved or not (`Loan_Status`). The data includes demographic, financial, and credit-related features of applicants.

## 📂 Dataset

- File: `loan_approval.csv`
- Rows: 614
- Features: 13 input variables + 1 target variable (`Loan_Status`)
- Source: [Loan Prediction Dataset – Analytics Vidhya](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/) (or your own source if different)

## 🔍 Features

| Feature | Description |
|--------|-------------|
| Gender | Male/Female |
| Married | Marital status |
| Dependents | Number of dependents |
| Education | Graduate/Not Graduate |
| Self_Employed | Self-employed status |
| ApplicantIncome | Income of applicant |
| CoapplicantIncome | Income of coapplicant |
| LoanAmount | Loan amount (in thousands) |
| Loan_Amount_Term | Term of the loan (in months) |
| Credit_History | Credit history (1 = good, 0 = bad) |
| Property_Area | Urban/Semiurban/Rural |
| Loan_Status | Target (Y = Approved, N = Not Approved) |

## 🛠️ Methodology

- Data Cleaning
  - Handled missing values with imputation
  - Converted categorical variables using Label Encoding
- Exploratory Data Analysis (EDA)
  - Visualized feature distributions
  - Checked class imbalance and correlations
- Model Building
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
- Model Evaluation
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

## 📊 Results

All models were evaluated using accuracy and F1-score. The Random Forest model showed the best performance on the test data, with good precision and recall.

## 📁 Files

- `Loan_Prediction.ipynb`: Jupyter notebook with full analysis and modeling
- `loan_approval.csv`: Raw dataset used
- `README.md`: Project overview and details

## 📌 Future Work

- Use XGBoost or GridSearchCV for hyperparameter tuning
- Implement cross-validation
- Deploy the model using Flask or Streamlit for real-time predictions

## 👨‍🎓 Author

**Hemanshu Patil**  
M.Sc. Statistics, MIT World Peace University, Pune  
[GitHub](https://github.com/hemanshupatil-Statistician) | [LinkedIn](https://www.linkedin.com/in/hemanshupatil)
