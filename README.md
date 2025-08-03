# 🥗 NutriClass: Food Classification Using Nutritional Data

A machine learning project to classify food items based on their nutritional content using traditional supervised learning models.

---

## 📌 Project Overview

> **Objective**: Predict the type of food or meal (e.g., breakfast, lunch, snack) using its nutritional features like calories, fat, sugar, protein, etc.

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| `Python` | Programming Language |
| `Pandas`, `NumPy` | Data Handling |
| `Matplotlib`, `Seaborn` | Data Visualization |
| `Scikit-learn` | Machine Learning Models |
| `XGBoost` | Boosting Model |
| `Jupyter Notebook` | Development Environment |

---

## 🔄 Workflow Summary

### ✅ Step 1: Data Exploration
- Checked dataset structure, class distribution
- Displayed random samples by meal type

### ✅ Step 2: Data Preprocessing
- Handled missing values and duplicates
- Outliers capped using **Winsorization** (1st and 99th percentiles)
- Standardized numerical features

### ✅ Step 3: Feature Engineering
- PCA applied to reduce dimensionality while preserving 95% variance
- Label encoding for target column

### ✅ Step 4: Model Training & Evaluation
Trained and compared:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  
- SVM  
- XGBoost  
- Gradient Boosting

---

## 🏆 Best Performing Model

| Model | Accuracy |
|-------|----------|
| 🌟 **Gradient Boosting** | **96.67%** |
| Random Forest, KNN, Decision Tree | 93.33% |
| XGBoost | 93.33% |
| SVM | 93.33% |

---

## 📊 Visuals

- Confusion matrix plotted using `seaborn`
- Feature importance visualized using bar plots
- PCA variance preservation chart (optional)

---

## ✅ Conclusion

> Gradient Boosting emerged as the most accurate model for classifying food based on nutrition.  
> Preprocessing steps like winsorization and PCA significantly boosted overall performanc

---

## 📁 Project Structure

