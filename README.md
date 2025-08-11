# Loan_Approval_Prediction

📌 **Project Overview**
This project aims to predict whether a loan application will be approved based on applicant details such as credit history, income, loan amount, and employment status.
Using machine learning, this solution helps financial institutions automate and speed up their loan approval process while maintaining fairness and accuracy.

📖 **Story Behind the Project**
Imagine you work in the loan approval department of a bank that receives hundreds of applications daily.
Manually verifying each applicant’s financial details is slow and error-prone — one wrong decision could mean a loss for the bank or unfair rejection for a customer.

This model automates the process with over 90% accuracy, reducing decision-making time and increasing efficiency.
It highlights the most influential factors — such as credit history, applicant income, and loan amount — helping banks make faster, fairer, and data-driven decisions.

⚙️ **Workflow**
1. Data Collection & Understanding
Loaded and explored loan application data.
Checked data distribution, missing values, and target variable imbalance.

2. Data Preprocessing
Encoded categorical variables into numerical format.
Scaled numerical features for better model performance.
Balanced the dataset using SMOTE to handle class imbalance.

3. Model Development
Models tried:
Random Forest Classifier (with class_weight='balanced')
Hyperparameter tuning done using RandomizedSearchCV.

4. Model Evaluation
Metrics Used:
Accuracy Score
Classification Report (Precision, Recall, F1-score)
Confusion Matrix
ROC Curve & AUC Score
Best Model: Random Forest Classifier with ~0.90 accuracy on test data.

5. Key Insights
Credit history is the most important factor in loan approval.
Higher applicant income and lower loan amount improve approval chances.

📊 **Model Performance**
| Metric               | Score  |
| -------------------- | ------ |
| Accuracy             | 90%    |
| AUC Score            | 0.85   |
| Precision (Approved) | ~0.93 |
| Recall (Approved)    | ~0.93 |

📂 **Files in This Repository**
Loan_Prediction.ipynb — Full Python notebook with data preprocessing, model building, and evaluation.

💡 **How to Run the Project**
Open the Jupyter Notebook and run the cells in order
jupyter notebook Loan_Prediction.ipynb
