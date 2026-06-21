# 📊 Customer Churn Prediction & Market Basket Analysis Platform

An interactive data science project that combines:

- Customer Churn Prediction (Supervised Learning)
- Market Basket Analysis (Unsupervised Learning)

Built using Python and deployed through a Streamlit-based interface.

---

# 📁 Repository Structure

- app.py → Streamlit web application interface  
- terminal_project_notebook.ipynb → Main analysis notebook for both modules  
- terminal_project_report final.docx → Final project report  
- Telco-Customer-Churn.xlsx → Telecom churn dataset  
- groceries.txt → Market basket analysis dataset  
- requirements.txt → Python dependencies  

---

# 📌 Project Overview

This project integrates two core data science tasks:

## 🔹 1. Customer Churn Prediction
Predict whether a telecom customer will leave the service using machine learning models trained on customer behavior data.

## 🔹 2. Market Basket Analysis
Discover product associations from transaction data using association rule mining techniques.

---

# 📊 Dataset Details

## 📞 Churn Dataset
- Source: IBM Telco Customer Churn dataset  
- Contains customer demographics, services, and billing details  
- Target variable: Churn (Yes/No)

## 🛒 Market Basket Dataset
- Grocery transaction dataset  
- Contains purchase baskets  
- Used for association rule mining

---

# 🧹 Data Processing

## Churn Prediction:
- Missing value handling  
- Label encoding for categorical variables  
- Feature scaling  
- Data balancing techniques (if applied in notebook)  

## Market Basket Analysis:
- Transaction formatting  
- Frequent itemset mining  
- Association rule generation  

---

# 🤖 Machine Learning Models

## 🔹 Churn Prediction Models
- Decision Tree  
- Logistic Regression  
- Support Vector Machine (SVM)  

## 🔹 Market Basket Analysis Methods
- Apriori Algorithm  
- FP-Growth Algorithm  

---

# 📈 Outputs

## Customer Churn Prediction:
- Predicts probability of churn  
- Evaluates performance using classification metrics  

## Market Basket Analysis:
- Frequent itemsets  
- Association rules  
- Metrics: support, confidence, lift  

---

# 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Streamlit  
- MLxtend  
- Matplotlib  
- Seaborn  

# ⚙️ Installation

### 1. Clone the repository

```bash
git clone <your-repo-link>
cd <repo-folder>
```
### 2. Install dependencies
pip install -r requirements.txt
### 3. Run application
streamlit run app.py

# 📌 Key Insights
- Proper preprocessing significantly improves churn prediction performance
- Tree-based models handle churn classification effectively
- Market Basket Analysis reveals strong product relationships using lift values
- Apriori and FP-Growth produce similar results with slight efficiency differences

# 🚀 Future Improvements
- Hyperparameter tuning using GridSearchCV
- Ensemble models for churn prediction
- Improved Streamlit UI/UX
- Larger datasets for deeper association mining
- Deployment on cloud platforms
