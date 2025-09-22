# Pandas Data Cleaning Project

This project demonstrates basic **data cleaning** operations using **Python** and **Pandas**.

## 📊 Dataset
A sample CSV file (`sample_data.csv`) is used that contains:
- Names
- Age
- Gender
- Date of Birth
- Score

## 🧹 Cleaning Steps
The script `pandas_clean.py` performs:
1. Load CSV and parse **Date_of_Birth** as a datetime object.
2. Check and count **missing values**.
3. Clean text columns (e.g., `Gender` to lowercase & remove spaces).
4. Convert **Age** and **Score** to numeric values.
5. Rename columns to **lowercase** and replace spaces with `-`.
6. Remove **duplicate** rows.
7. Drop rows with **missing values**.
8. Save the cleaned data to a new file `clean_data.csv`.

## 🚀 How to Run
```bash
python pandas_clean.py
