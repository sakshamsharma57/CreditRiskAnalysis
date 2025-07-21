# 🏦Credit Risk Analysis for Loan distribution

Data Science project for calculation of Probability of Default for Customers taking Loan from Bank using different algorithms.<br>
_AIM : To calculate probability of default for the customer for a bank in your base._


![banner](https://github.com/sakshamsharma57/CreditRiskAnalysis/blob/7a58865a103df04877bfec4489d75fbe5c6ab2a6/Asset/Banner.jpeg)

![Type of ML](https://img.shields.io/badge/Type%20of%20ML-Regression-red)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CkvyS1qdm_q7cq_ww8uBevzNnJYbDuQt#scrollTo=Vd7NOoHB5M6c)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
<br>
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)


## 📌 Objective

This project aims to build a machine learning model that can predict the **credit risk** associated with loan applicants — helping financial institutions make informed, data-driven lending decisions. By analyzing historical loan data, payment behavior, and socio-economic attributes, we classify individuals based on how risky it is to give them a loan.

### 🔸 Correspondingly, giving score to each customer based on **_Probablity of Default (PD)_**. High PD people getting low score and low PD people getting high score

> 🔍 This project mirrors the kind of credit scoring systems used by **major banks and lending institutions** in India and around the world.

---

## 🧠 Why Credit Risk Analysis so relevent in finnace

Credit risk assessment is the cornerstone of loan underwriting. Misjudging an applicant's ability to repay can lead to significant financial losses. Traditional methods are often manual and prone to bias or inefficiency. This project solves real-world problems such as:

- Identifying **potential defaulters** before loan disbursement.
- Reducing **Non-Performing Assets (NPAs)** for banks.
- Enabling **faster, automated loan approvals**.
- Minimizing **manual errors and biases** in risk scoring.

---

## 🔍 Project Workflow

### 1. 🧾 Data Collection

Data source

- [Kaggle.com](https://www.kaggle.com/)

Collected anonymized data containing:
- **Credit history**
- **Payment behavior**
- **Loan purpose**
- **Income levels**
- **Demographic details** (age, job, marital status, etc.)

> Dataset was similar to those used in real-world credit scoring datasets (e.g., UCI, LendingClub, FICO scores).

---

### 2. 🧼 Data Cleaning & Preprocessing
- Handled missing values
- Categorical encoding (Label Encoding / One-Hot)
- Normalization / scaling
- Removed outliers and inconsistencies

---

### 3. 📊 Exploratory Data Analysis (EDA)
- Correlation heatmaps to detect feature dependencies
- Risk distribution by age, job, and credit score
- Visualized default trends based on past payment history
- Class imbalance analysis (Good vs. Bad Credit)

---
### 🔸 Income to Age distribution
![banner](https://github.com/sakshamsharma57/CreditRiskAnalysis/blob/7a58865a103df04877bfec4489d75fbe5c6ab2a6/Asset/income-age%20graph.png)
### 🔸 Age to Debt distribution
![banner](https://github.com/sakshamsharma57/CreditRiskAnalysis/blob/7a58865a103df04877bfec4489d75fbe5c6ab2a6/Asset/age-debt%20graph.png)

---

## ⚙️ Models Implemented

### 🔸 Random Forest Classifier 🌲
An ensemble learning method that uses multiple decision trees to vote on predictions. It handles feature importance well and resists overfitting.

### 🔸 Support Vector Machine (SVM) ✴️  
Best suited for high-dimensional classification problems. Separates risky vs. non-risky borrowers using an optimal hyperplane.

### 🔸 Logistic Regression 📈  
Used as a baseline model for binary classification. Simple and interpretable, often used in financial institutions for transparency.

---

## 🧪 Model Evaluation

| Metric               | Description                            |
|----------------------|----------------------------------------|
| **Accuracy**         | Overall correctness of predictions     |
| **Precision/Recall** | How well the model identifies defaulters |
| **F1 Score**         | Balance between Precision & Recall     |
| **ROC-AUC Score**    | Separability between risky and safe applicants |

> 🚀 The **Logistic Regression Algorithm** emerged as the best performer due to its Binary classification.
---

### 🔸 Logistic regresion- Confusion matrix
![Logictic regression](https://github.com/sakshamsharma57/CreditRiskAnalysis/blob/b011344417d272240eb329ca74ce21351824a6c3/Asset/WhatsApp%20Image%202025-07-16%20at%2002.39.01_b7511309.jpg)

---

## ✴️ Probablity of Default (PD) scores

To quantify creditworthiness, we assign a credit score to each customer based on their Probability of Default (PD). This scoring mechanism is designed so that:
- Customers with a higher PD (i.e., higher risk of default) receive a lower credit score.
- Customers with a lower PD (i.e., more reliable borrowers) receive a higher credit score.
- This helps financial institutions quickly interpret risk levels and make data-driven lending decisions.

![PD Scores](https://github.com/sakshamsharma57/CreditRiskAnalysis/blob/b2d715d3b023432d310aa89da2378e6e0318e4fd/Asset/WhatsApp%20Image%202025-07-20%20at%2018.08.14_805a2557.jpg)

---

## 🔍 Key Insights

- **Past payment behavior** is the strongest predictor of future risk.
- Applicants with **unstable income sources** and **no prior credit history** are more likely to default.
- **Loan purpose** (e.g., business vs. personal) also significantly influences risk.
- **Class imbalance** is a major challenge — most applicants have good credit, but detecting the few bad ones is critical.

---

## 📈 Visualizations

- 📉 Credit Score Distribution
- 🔥 Feature Importance (Random Forest)
- ✅ Confusion Matrices for all models
- 📊 Risk by Income & Job Type

---

## ✅ Conclusion

This project successfully built a machine learning pipeline to predict credit risk with high accuracy and interpretability. It reflects the kind of risk modeling done in real-world banking systems, helping lenders:

- Reduce defaults
- Automate decisions
- Improve customer experience
- Maintain regulatory compliance

---

## 💬 Final Thoughts

Understanding and managing credit risk is **mission-critical** for any lending institution. By combining statistical rigor with machine learning, this project demonstrates how **AI can responsibly power modern finance** — minimizing risk while expanding access to credit.

---
