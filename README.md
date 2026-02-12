# 💳 CreditWise: Intelligent Loan Approval System

CreditWise is a **machine learning–powered loan approval system** designed to help financial institutions make **faster, unbiased, and data-driven lending decisions**.  
It replaces error-prone manual verification with an automated pipeline that evaluates applicant risk using demographic, financial, employment, and credit data.

---

## 📌 Problem Statement

**SecureTrust Bank**, a mid-sized financial institution, faced challenges with its manual loan approval process:

- ❌ Rejection of eligible, low-risk applicants (business loss)
- ⚠️ Approval of high-risk applicants (financial loss)
- 🕒 Slow decision-making and human bias

**CreditWise** solves this by predicting loan approval outcomes with high accuracy using historical data.

---

## 🎯 Objective

- Automate the loan eligibility decision process  
- Reduce human bias and approval time  
- Minimize financial risk for the bank  
- Improve approval consistency across urban and rural applicants  

---

## 📊 Dataset Description

The model is trained on historical loan application data with the following features:

| Category | Features |
|--------|----------|
| **Identity** | Applicant ID, Gender, Age, Marital Status, Dependents |
| **Financials** | Applicant Income, Co-applicant Income, Savings, DTI Ratio |
| **Employment** | Employment Status, Education Level, Employer Category |
| **Credit History** | Credit Score, Existing Loans |
| **Loan Details** | Loan Amount, Loan Term, Loan Purpose, Collateral Value |
| **Geography** | Property Area (Urban / Semi-Urban / Rural) |
| **Target Variable** | Loan Status (1 = Approved, 0 = Rejected) |

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - Pandas, NumPy – Data manipulation  
  - Matplotlib, Seaborn – Exploratory Data Analysis  
  - Scikit-Learn – Model building & evaluation  
- **Environment:** Jupyter Notebook / VS Code  

---

## 🚀 Key Features

- 📊 **Exploratory Data Analysis (EDA)**  
  - Visualized the impact of credit score, income, and DTI ratio on loan approvals  

- 🧹 **Data Preprocessing**  
  - Handled missing values  
  - One-hot encoding for categorical variables  
  - Feature scaling and normalization  

- 🧠 **Feature Engineering**  
  - Total household income  
  - Debt-to-income balance metrics  

- 🤖 **Predictive Modeling**  
  - Logistic Regression  
  - Random Forest Classifier  
  - XGBoost (optional)  

- ⚖️ **Risk-Aware Evaluation**  
  - Accuracy  
  - Precision  
  - Recall  

---

## 📈 Methodology

1. **Data Cleaning**  
   - Removed outliers in income and loan amount  
   - Ensured feature consistency  

2. **Feature Engineering**  
   - Created derived financial indicators  
   - Improved predictive performance  

3. **Model Selection**  
   - Compared multiple classifiers  
   - Selected best-performing model based on recall and precision  

4. **Model Evaluation**  
   - Focused on minimizing false approvals to reduce financial risk  

---

## 🏁 How to Run the Project

### 1️⃣ Clone the Repository
```
git clone https://github.com/yourusername/CreditWise-Loan-System.git
cd CreditWise-Loan-System
```

### 2️⃣ Install Dependencies
```
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook
```
jupyter notebook
```

### Open and run:
```
CreditWise_Loan_Approval.ipynb
```

### 📂 Project Structure
```
CreditWise-Loan-System/
│
├── credit_wise.ipynb
│
├── loan_approval_data.xlsx
│
├── Problem Statement (Part-1).png
│
├── Problem Statement (Part-2).jpg
│
├── requirements.txt
│
└── README.md
```


```bash
git clone https://github.com/shivam999876/CreditWise-Loan-System.git
cd CreditWise-Loan-System
