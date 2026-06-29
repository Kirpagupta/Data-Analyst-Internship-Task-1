# Data Cleaning and Preprocessing - Task 1

## 📌 Overview

This project was completed as part of my **Data Analyst Internship - Task 1**. The objective was to clean and preprocess a raw dataset by identifying and handling common data quality issues such as missing values, inconsistent formatting, duplicate records, and incorrect data types.

---

## 📂 Dataset

**Dataset:** Netflix Movies and TV Shows

The dataset contains information about Netflix content, including:
- Show ID
- Type
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

---

## 🎯 Objective

Prepare the raw dataset for analysis by performing data cleaning and preprocessing.

---

## 🛠️ Tools Used

- Python 3
- Pandas
- Jupyter Notebook

---

## ✅ Data Cleaning Steps Performed

### 1. Missing Value Handling
- Identified missing values using `isnull().sum()`.
- Filled missing values in:
  - `director`
  - `cast`
  - `country`
  - `rating`
- Removed rows with missing values in:
  - `date_added`
  - `duration`

---

### 2. Duplicate Record Check
- Checked for duplicate rows using `duplicated().sum()`.
- No duplicate records were found in the dataset.

---

### 3. Date Formatting
- Removed unnecessary spaces from the `date_added` column.
- Converted the column to the `datetime` data type for consistency.

---

### 4. Column Standardization
- Renamed column headers by:
  - Converting all names to lowercase.
  - Replacing spaces with underscores.

Example:

Show ID → show_id

Release Year → release_year

---

### 5. Data Type Verification
Verified that each column had the appropriate data type.
- `date_added` → datetime
- `release_year` → integer
- Text columns → object

---

### 6. Exported Clean Dataset
Saved the cleaned dataset as:

```
cleaned_netflix_dataset.csv
```

---

## 📁 Repository Structure

```
├── netflix_titles.csv
├── cleaned_dataset.xls
├── task1.ipynb
└── README.md
```

---

## 📊 Outcome

The dataset was successfully cleaned and prepared for further data analysis and visualization. The preprocessing steps improved the overall quality, consistency, and usability of the data.

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Missing Value Treatment
- Duplicate Detection
- Data Type Conversion
- Data Formatting
- Pandas
- Python
- Jupyter Notebook

---

## 👩‍💻 Author

**Kirpa Gupta**

Data Analyst Intern
