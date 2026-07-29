# 💳 PeerLoanKart - Loan Default Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting whether a borrower is likely to fully repay a loan using historical lending data from **PeerLoanKart**, a peer-to-peer lending platform. The objective is to help financial institutions reduce credit risk and minimize Non-Performing Assets (NPAs) by identifying high-risk loan applicants before loan approval.

**Domain:** Banking | FinTech | Risk Analytics

---

## 🎯 Business Problem
PeerLoanKart connects borrowers with investors. One of the biggest challenges is identifying borrowers who are likely to default on their loans. A poor lending decision increases NPAs and financial losses.

The goal of this project is to build a machine learning model that accurately predicts loan repayment status, enabling better lending decisions and reducing default risk.

---

## 🚀 Solution Approach
- Performed data cleaning and preprocessing.
- Conducted Exploratory Data Analysis (EDA) to identify important patterns.
- Applied feature engineering and encoded categorical variables.
- Trained multiple classification models.
- Optimized the best-performing model using hyperparameter tuning.
- Selected **XGBoost Classifier** as the final model based on its superior performance.

---

## 📂 Dataset Information

The dataset contains historical borrower information, including:

- Credit Policy
- Loan Purpose
- Interest Rate
- Monthly Installment
- Annual Income
- Debt-to-Income Ratio
- FICO Credit Score
- Credit Line History
- Revolving Balance
- Revolving Utilization
- Credit Inquiries
- Delinquencies
- Public Records

**Target Variable**
- **not.fully.paid**
  - **0:** Loan Fully Paid
  - **1:** Loan Not Fully Paid

---

## 📊 Exploratory Data Analysis
Key analyses performed include:
- Loan repayment distribution
- FICO score analysis
- Interest rate distribution
- Income vs Default analysis
- Debt-to-Income ratio analysis
- Correlation heatmap
- Feature importance visualization

---

## 🤖 Machine Learning Models
The following models were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost Classifier

**Best Performing Model:** XGBoost

---

## 📈 Model Performance
- Accuracy: **94%**
- High precision and recall for identifying risky borrowers
- Reduced false approvals for high-risk loan applicants

---

## 🔍 Key Insights
- Borrowers with lower FICO scores are more likely to default.
- Higher debt-to-income ratios significantly increase default risk.
- Credit policy plays a crucial role in loan repayment prediction.
- Interest rate, annual income, installment amount, and repayment history are among the most influential features.
- XGBoost provided the highest predictive performance compared to other classification models.

---

## 💼 Business Impact
- Reduced risk of Non-Performing Assets (NPAs).
- Improved loan approval decisions using predictive analytics.
- Helped lenders identify high-risk borrowers before loan disbursement.
- Increased operational efficiency through automated risk assessment.
- Enabled more profitable and data-driven lending strategies.

---

## ✅ Conclusion
This project successfully developed a machine learning solution to predict loan repayment risk using historical borrower data. After preprocessing, feature engineering, and model optimization, the XGBoost model achieved approximately **94% accuracy** in classifying loan repayment status.

To improve readability, the predicted output was converted into user-friendly labels (**"Paid"** and **"Not Paid"**) and merged with the original dataset. This allows lenders and investors to easily interpret prediction results and make informed lending decisions.

---

## 🚀 Future Improvements
- Deploy the model using Flask or FastAPI.
- Build an interactive Streamlit dashboard.
- Integrate SHAP for explainable AI.
- Implement real-time loan risk prediction APIs.
- Retrain the model periodically using new lending data.

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📌 Skills Demonstrated
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning
- Classification
- Hyperparameter Tuning
- Model Evaluation
- Business Insights
- Predictive Analytics
