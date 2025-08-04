# titanic-data-cleaning
Titanic Data Cleaning &amp; Preprocessing – Internship Task 1 | Missing value handling, encoding, normalization, and outlier removal using Python, Pandas, and Scikit-learn
Titanic Data Cleaning & Preprocessing – Internship Task 1 | Missing value handling, encoding, normalization, and outlier removal using Python, Pandas, and Scikit-learn. 🚢 Titanic Dataset - Data Cleaning & Preprocessing

This repository contains my submission for Task 1 of the AI & ML Internship focused on Data Cleaning & Preprocessing using the Titanic dataset.

📌 Objective

To clean and preprocess the Titanic dataset by handling missing values, encoding categorical variables, scaling features, and removing outliers to prepare the data for machine learning models.

📁 Files Included
titanic.csv - Raw dataset (or link to it)
titanic_cleaned.csv - Final cleaned dataset
titanic_preprocessing.ipynb - Jupyter Notebook with all preprocessing steps
README.md - This file
🧪 Steps Performed
1. Dataset Loading
Loaded the Titanic dataset using pandas.
2. Data Exploration
Used .info(), .describe(), and .isnull().sum() to understand the structure and missing data.
3. Handling Missing Values
Filled missing Age values using median.
Imputed missing Embarked values using mode.
Dropped the Cabin column due to excessive null values.
4. Categorical Encoding
Applied One-Hot Encoding on Sex and Embarked columns.
5. Feature Scaling
Scaled Age and Fare columns using StandardScaler (Z-score standardization).
6. Outlier Detection & Removal
Detected outliers using boxplots.
Removed outliers using Z-score method (alternative IQR method provided).
📊 Libraries Used
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy
📥 Dataset Source
Titanic Dataset on Kaggle

✅ Output
A clean and ready-to-use dataset saved as titanic_cleaned.csv.
💡 Learning Outcomes
Gained hands-on experience with real-world data cleaning.
Understood how preprocessing improves model quality and efficiency.
