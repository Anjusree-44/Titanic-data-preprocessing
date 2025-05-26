# Titanic-data-preprocessing
# 🚢 Titanic Data Cleaning & Preprocessing

This repository contains the solution for **Task 1: Data Cleaning & Preprocessing** as part of the **AI & ML Internship Program**.

## 📌 Objective

To learn how to clean and prepare raw data for Machine Learning by handling missing values, encoding categorical features, scaling numerical features, and detecting/removing outliers.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `Titanic data preprocessing.py`  | vistual studio code |
| `Titanic.csv` | Raw Titanic dataset (upload manually from Kaggle) |
| `cleaned_titanic.csv` | Final cleaned dataset after preprocessing |
| `README.md` | You are here! Documentation and explanation of the task |

---

## 🧰 Tools Used   

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **Google Colab** or **VS Code**

---

## 🔧 Steps Performed

1. **Loaded Dataset** from `Titanic.csv`
2. **Explored Basic Info**: shape, null values, data types
3. **Handled Missing Values**:
   - `Age`: filled with median
   - `Cabin`: filled with 'Unknown'
   - `Embarked`: filled with mode
4. **Dropped Irrelevant Columns**: `Name`, `Ticket`
5. **Encoded Categorical Columns**:
   - Label encoding for `Sex`
   - One-hot encoding for `Embarked` and `Cabin`
6. **Normalized Numerical Features**:
   - `Age` and `Fare` scaled using `MinMaxScaler`
7. **Visualized and Removed Outliers**:
   - Used boxplots and IQR method
8. **Saved Cleaned Dataset**: `cleaned_titanic.csv`

---

## 📊 Sample Output (Cleaned Data)

| PassengerId | Survived | Pclass | Sex | Age | Fare | ... |
|-------------|----------|--------|-----|-----|------|-----|
| 1           | 0        | 3      | 1   | 0.25| 0.014| ... |

---

## 🔗 Dataset Source

- [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)


---

## 📚 Interview Prep (Topics to Study)

- Types of missing data
- Categorical encoding (One-hot vs Label encoding)
- Normalization vs Standardization
- Outlier detection methods
- Why preprocessing is crucial
- Handling data imbalance
- How preprocessing affects model accuracy

---

## ✅ Author

- Internship Participant: Katta Anju Sree
- Internship Program: *AI & ML Internship by Elevate Labs

