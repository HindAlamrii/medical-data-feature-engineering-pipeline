# Medical Data Feature Engineering Pipeline

## 🚀 Project Overview
This project builds a complete feature engineering pipeline for a real-world healthcare dataset containing over 900K records.

The goal is to prepare high-quality data for predicting LDL Cholesterol using machine learning.

---

## 🧠 Problem
Healthcare datasets are messy:
- Missing values (millions)
- High-cardinality categorical variables
- Duplicate records
- Mixed data types

---

## ⚙️ Solution
A robust pipeline was developed to handle real-world data issues:

- Data Cleaning (duplicates, inconsistent formats)
- Missing Value Imputation
- Feature Transformation (scaling, encoding)
- Feature Engineering (date features, interactions)
- Feature Selection (top 70 features)
- Data Leakage Prevention (strict train-test separation)

---

## 📊 Results
- Original Data: 929,107 rows, 108 columns
- Final Features: 70
- Training Set: 253,784 records
- Testing Set: 63,446 records
- Null Values: Reduced to 0

---

## 📈 Key Insights
- Strong correlation between lipid-related features (LDL, HDL, Cholesterol)
- Outliers significantly distorted distributions and were successfully removed
- Feature selection improved efficiency without losing predictive power

---

## 🧪 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

---

## 📁 Project Structure
- notebooks/ → full workflow
- src/ → reusable pipeline
- outputs/ → processed datasets
- report/ → full analysis

---

## ⚠️ Important Note
All preprocessing steps were applied after train-test split to prevent data leakage.

---

## 👩‍💻 Author
Hind
