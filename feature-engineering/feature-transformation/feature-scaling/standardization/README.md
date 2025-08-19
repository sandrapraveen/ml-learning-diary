# Standardization in Machine Learning 

This repository contains my notebook **`standardization.ipynb`**, where I explore the concept of **feature standardization** — one of the most important preprocessing steps in Machine Learning.

---

## 📌 What’s inside?
In the notebook, I cover:
- ✨ Why standardization is important  
- 📊 How to use `StandardScaler` from scikit-learn  
- 🔎 The difference between `fit`, `transform`, and `fit_transform`  
- ⚖️ Effect of standardization on different ML models  
- 🧪 Experiments comparing models **before vs. after scaling**

---

## 🛠️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔬 Key Learnings
- Decision Trees and Random Forests are **scale-invariant** 🌳  
- Logistic Regression, SVM, KNN, and Neural Networks **need scaling** to perform well  
- Standardization makes training more **stable and faster**  
- Avoid **data leakage**: use `fit_transform()` on the training set, and only `transform()` on the test set  

---
