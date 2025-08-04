# Internship Task 1: Data Preprocessing on Titanic Dataset

This repository contains my first task as an AI/ML intern. The objective was to perform comprehensive **data preprocessing** on the Titanic dataset, which is a foundational step in any machine learning pipeline.

## 📌 Task Objectives

- Load and understand the dataset
- Handle missing/null values
- Encode categorical variables (e.g., `Sex`, `Embarked`)
- Normalize numerical features (e.g., `Age`, `Fare`)
- Detect and remove outliers
- Drop irrelevant or high-cardinality features

## 🧠 Key Concepts Used

- **Null Value Handling:** Used methods like mean/mode imputation to fill missing values.
- **Encoding:** One-hot encoding for categorical columns using `pd.get_dummies()`.
- **Normalization:** Applied MinMaxScaler for scaling numerical features.
- **Outlier Detection:** Used IQR method to detect outliers in the `Fare` column.
- **Feature Selection:** Dropped `PassengerId`, `Name`, and `Ticket` due to low predictive value.

## 📂 Files

- `Internship(Task_1).ipynb`: Main notebook with complete preprocessing pipeline.

## ✅ Final Outcome

A clean and preprocessed Titanic dataset, ready for model building or exploratory analysis.

## ✍️ Author

Aditya Singh  
AI & ML Intern  
[LinkedIn]( https://linkedin.com/in/aditya-singh-5927871ab)
