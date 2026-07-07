# Financial-Loan-Risk-Prediction
Summative Lab: Financial Loan Risk Prediction using Machine Learning
## Project Overview
This project develops a machine learning model to predict whether a loan applicant is likely to default on a loan based on financial and demographic information. The objective is to help financial institutions make faster, more accurate, and data-driven lending decisions.

## Business Problem
Manual loan approval processes are often time-consuming and susceptible to human error. This project applies machine learning techniques to classify applicants as likely to default or not, reducing lending risk and improving decision-making.

## Dataset
The dataset contains customer financial and demographic information, including:
- Income
- Loan Amount
- Credit Score
- Interest Rate
- Employment Status
- Net Worth
- Debt-to-Income Ratio
- Education Level
- Credit History
- and other financial attributes.

## Project Workflow
- Business Understanding
- Data Understanding
- Data Cleaning & Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Model Development
- Hyperparameter Tuning (Grid Search & Random Search)
- Model Evaluation
- Feature Importance Analysis
- Final Business Recommendations

## Models Evaluated
- Logistic Regression
- Decision Tree
- Random Forest
- Logistic Regression (Grid Search)
- Logistic Regression (Random Search)
- Random Forest (Grid Search)
- Random Forest (Random Search)

## Model Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- Cross Validation
- ROC Curve

## Final Results
The Logistic Regression model achieved the best overall performance with:
- Accuracy: *97%*
- Precision: *93%*
- Recall: *93%*
- F1-Score: *93%*
- ROC-AUC: *0.99*

Hyperparameter tuning produced minimal improvement, indicating that the default Logistic Regression model was already well optimized for this dataset.

## Business Recommendations
- Adopt the Logistic Regression model for loan default prediction.
- Use the model as a decision-support tool rather than replacing human judgment.
- Monitor model performance regularly as new customer data becomes available.
- Retrain the model periodically to maintain predictive performance.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Author
*Viola Rono*