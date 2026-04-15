# 📊 Credit Wise – Loan Approval Prediction

---

## 🔹 Project Title
Credit Wise – Loan Approval Prediction

---

## 👥 Team Members

- Maharudra Patil - 48
- Yash Umdale - 62
- Kartik Swami - 59

---

## 📝 Initial Proposal Summary

This project aims to develop a machine learning model to predict loan approval status based on applicant details such as income, credit history, and loan amount.

The objective is to automate loan approval decisions, reduce financial risk, and improve efficiency in financial institutions.

---

# 📂 Phase 2: Data Collection & Preprocessing

---

## 📊 Dataset Description

- Source: Kaggle Loan Dataset  
- Type: Structured dataset  

### Features:
- Applicant Income  
- Co-applicant Income  
- Loan Amount  
- Credit History  
- Employment Details  

### Target Variable:
- Loan_Status (Approved / Not Approved)

---

## 🧹 Preprocessing Summary

- Handled missing values  
- Removed inconsistencies and duplicates  
- Encoded categorical variables using one-hot encoding  
- Applied feature scaling using StandardScaler  
- Prepared dataset for machine learning models  

---

## 📁 Files Added in This Phase

- credit_wise.ipynb  
- data_preprocessing.ipynb (if separate)  
- requirements.txt  
- Dataset file OR dataset link  

---

# 📊 Phase 3: Exploratory Data Analysis (EDA)

---

## 📈 EDA Notebook

- EDA.ipynb contains:
  - Data visualization  
  - Pattern analysis  
  - Feature relationships  

---

## 📁 Visualization Outputs

Stored in /outputs/ folder:

- Loan approval distribution graph  
- Correlation heatmap  
- Feature comparison plots  

---

## 🔍 Major EDA Findings

- Credit history is the strongest predictor of loan approval  
- Higher income increases chances of approval  
- Financial features have high influence on decisions  
- Some variables show moderate correlation  

---

## 💡 Key Observations

- Applicants with good credit history are more likely to get approved  
- Income plays a significant role in approval decisions  
- Data shows clear patterns useful for prediction  
- Feature relationships help improve model performance  

---

# ⚙️ Next Phases (Brief)

## 🤖 Model Building
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  

## 📊 Model Evaluation
- Accuracy, Precision  
- Best Model: Naive Bayes  

---

# 📁 Project Structure

Credit-Wise/
│── credit_wise.ipynb
│── EDA.ipynb
│── dataset.csv / dataset link
│── requirements.txt
│── outputs/
│   ├── graphs/
│── README.md

---

# ▶️ How to Run

1. Clone repository  
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn  
3. Open Jupyter Notebook  
4. Run credit_wise.ipynb  

---

# 🎯 Summary

This project demonstrates how machine learning can automate loan approval decisions by analyzing applicant data, improving efficiency, and reducing financial risk.
