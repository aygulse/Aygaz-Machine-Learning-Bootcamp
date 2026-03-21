# 🚀 Fraud Detection with Machine Learning

This project was developed as part of the Aygaz Machine Learning Bootcamp.  
It focuses on detecting fraudulent transactions using both supervised and unsupervised machine learning techniques.

---

## 📌 Problem

Online payment systems are vulnerable to fraudulent transactions, making accurate fraud detection critical for financial security and risk management.

---

## 🎯 Objective

To compare supervised and unsupervised machine learning approaches for fraud detection and identify the most effective method.

---

## 📊 Dataset

- **Source:** Kaggle – Online Payments Fraud Detection Dataset  
- Includes transaction data such as:
  - Transaction type  
  - Amount  
  - Account balances  
  - Fraud labels (`isFraud`)  

---

## ⚙️ Methods

### 🔹 Supervised Learning
- Logistic Regression  
- Used for binary classification (fraud vs non-fraud)

### 🔹 Unsupervised Learning
- K-Means Clustering  
- Used to identify hidden patterns and anomalies in data  

---

## 📈 Results

- Achieved **99.9% accuracy** using Logistic Regression  
- Detected **619 fraudulent transactions out of 1,620**  
- Identified **class imbalance problem** affecting fraud detection performance  

### Confusion Matrix

|          | Predicted 0 | Predicted 1 |
|----------|-------------|-------------|
| Actual 0 | 1,270,849   | 55          |
| Actual 1 | 1,001       | 619         |

---

## 🧠 Key Insights

- Supervised learning outperformed unsupervised learning for fraud detection  
- Logistic Regression proved effective for binary classification problems  
- Class imbalance significantly impacts recall in fraud detection  

---

## 💼 Business Impact

- Fraud detection systems can significantly reduce financial losses in online payment platforms  
- Improving recall is critical to catching fraudulent transactions  
- Even small improvements in detection rates can have high financial impact  

---

## 🚀 Future Improvements

- Apply advanced models such as Random Forest and XGBoost  
- Handle class imbalance using techniques like SMOTE  
- Improve recall for fraud detection  

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔗 Project Links

📊 Kaggle Notebook:  
https://www.kaggle.com/code/aygulse/aygaz-makine-renmesi-bootcamp-proje-kamp  

---

## 👩‍💻 Author

**Ayşegül Çelikyurt**  
Industrial & Computer Engineering Student  
