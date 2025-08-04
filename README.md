# netflix-data-cleaning-task

## 📌 Task Overview
This task is part of the Data Analyst Internship – Task 1: Data Cleaning and Preprocessing.

## ✅ Objective
To clean the raw Netflix dataset by:
- Handling missing values
- Removing inconsistencies
- Standardizing date formats
- Preparing the dataset for analysis

## 🔧 Steps Performed
- Replaced missing `director`, `cast`, and `country` with `"Unknown"` or `"Not listed"`
- Dropped rows with missing `date_added` or `duration`
- Converted `date_added` to `datetime` format
- Cleaned and standardized column names
- Verified all missing values and datatypes
- Exported final cleaned dataset as `netflix_cleaned.csv`

## 🛠 Tools Used
- Python
- Pandas
- Google Colab

## 📁 Files Included
- `netflix_cleaned.csv` – Cleaned dataset
- `netflix_cleaning.ipynb` – Colab notebook with code
- `README.md` – Project summary
