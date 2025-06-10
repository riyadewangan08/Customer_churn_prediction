# 📊 Customer Churn Prediction using Machine Learning
![Image](https://github.com/user-attachments/assets/6d871cd9-a346-4fac-a212-132cecf7da61)

## 📁 Project Overview

This project focuses on predicting customer churn using various classification algorithms. We analyze behavioral and demographic features of customers and apply supervised machine learning models to predict whether a customer is likely to churn or not.

---

## 📌 Objectives

- Perform data cleaning and preprocessing
- Encode categorical variables
- Train and evaluate multiple classification models
- Identify key drivers behind churn using feature importance
- Compare model performance with visualizations

---

## 📂 Dataset Information

The dataset includes the following key features:

- `Tenure`
- `PreferredLoginDevice`
- `CityTier`
- `WarehouseToHome`
- `CashbackAmount`
- `Complain`, `SatisfactionScore`, `NumberOfAddress`, etc.
- `Churn` (Target variable)

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🔎 Exploratory Data Analysis (EDA)

> ✔ Null checks, type conversion, and label encoding  
> ✔ Visualizations: boxplots, histograms, outlier removal  
> ✔ Distribution analysis of categorical and numerical columns  

_📸 Sample EDA Visualization_  
![EDA Plot](images/eda_sample.png)

---

## 🤖 Models Used

- Logistic Regression  
- Decision Tree  
- Random Forest ✅ (Best Accuracy)  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)

---

## 📈 Model Performance

| Model                | Accuracy  |
|---------------------|-----------|
| Logistic Regression | 86.06%    |
| Decision Tree       | 94.85%    |
| Random Forest       | 96.36% ✅ |
| KNN                 | 81.35%    |
| SVM                 | 84.10%    |

---

## 📊 Visualizations

### 🔹 Model Accuracy Comparison

![Model Accuracy](images/model_accuracy.png)

### 🔹 Feature Importance (Random Forest)

![Feature Importance](images/feature_importance.png)

### 🔹 Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

## 📌 Key Findings

- **Tenure**, **CashbackAmount**, and **WarehouseToHome** are the top churn indicators.
- Random Forest outperforms all other models in prediction accuracy.
- Business can target long-tenure and low cashback users for retention campaigns.

---

## 📝 Conclusion

An end-to-end churn prediction system was built using structured customer data. The Random Forest Classifier provided the best performance. Visualization and feature analysis helped gain insights into what affects customer churn the most.

---

## 🙌 Acknowledgments

- Thanks to open datasets and community notebooks for inspiration.
- Libraries: Scikit-learn, Matplotlib, Pandas, Seaborn

---

## 📬 Contact

**Created by:** Riya  
**Email:** [riyadew77@gmail.com](mailto:riyadew77@gmail.com)

---

> ✨ _Feel free to fork, clone, or contribute to this project!_
