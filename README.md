# Credit Card Fraud Detection 🚀  

This project focuses on detecting fraudulent credit card transactions using a **Logistic Regression** model. It is a practical implementation in the field of Machine Learning, aiming to secure financial transactions by identifying and preventing fraudulent activities.  

---

## 📌 **Overview**  
Credit card fraud detection is a critical task in the financial sector. Fraudulent transactions account for only a small fraction of the total data, making this a highly imbalanced classification problem. This project demonstrates how **Logistic Regression** can be used effectively to tackle this challenge, achieving a high accuracy of **93%**.  

---

## 🧠 **Project Details**  
### **Objective:**  
To develop a reliable model capable of detecting fraudulent transactions from historical data.

### **Dataset:**  
The dataset contains anonymized credit card transactions, including:  
- A mix of numerical features (e.g., V1, V2, ..., V28) obtained from PCA transformation.  
- Two columns: `Amount` (transaction value) and `Class` (target variable where 1 = Fraud, 0 = Legitimate).  
- Highly imbalanced data, with a significant majority of legitimate transactions.  

**Dataset Source:** [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)  

---

## 🔍 **Approach:**  

1. **Data Preprocessing:**  
   - Handled the imbalanced dataset using **SMOTE (Synthetic Minority Oversampling Technique)**.  
   - Normalized the `Amount` column for better model performance.  

2. **Feature Engineering:**  
   - Removed redundant or low-impact features.  
   - Performed exploratory data analysis to identify key patterns.  

3. **Evaluation:**  
   - Achieved **93% accuracy** on the validation dataset.  
   - Metrics evaluated include **Precision**, **Recall**, **F1-Score**, and **AUC-ROC**.  

---

## 📊 **Results**  
- **Accuracy:** 93%  

---

## ⚙️ **Technologies Used**  
- **Python**: Programming language.  
- **Pandas**: For data manipulation.  
- **NumPy**: For numerical operations.  
- **Scikit-Learn**: For model development and evaluation.  
- **Matplotlib & Seaborn**: For visualizations.  

---

## 📂 **Project Structure**  
- `data/`: Contains dataset files (if applicable).  
- `notebooks/`: Jupyter notebooks for EDA, model building, and evaluation.  
- `src/`: Python scripts for preprocessing, training, and evaluation.  
- `README.md`: Project documentation.  

---
