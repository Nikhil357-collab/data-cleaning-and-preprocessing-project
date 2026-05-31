# data-cleaning-and-preprocessing-project
Cleaned and preprocessed the Netflix Movies and TV Shows dataset using Python and Pandas by handling missing values, removing duplicates, standardizing formats, validating data types, and generating a clean analysis-ready dataset.
# Netflix Data Cleaning and Preprocessing Project

## Overview

This project demonstrates the complete data cleaning and preprocessing workflow on the Netflix Movies and TV Shows dataset. The objective is to transform raw data into a clean and structured format suitable for analytics, visualization, and machine learning applications.

---

## Dataset

Dataset: Netflix Movies and TV Shows

Source: Kaggle

The dataset contains information about Netflix content, including:

* Show ID
* Type
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre
* Description

---

## Project Objectives

* Identify and handle missing values
* Remove duplicate records
* Standardize text formatting
* Convert date columns into a consistent format
* Rename column headers using snake_case convention
* Validate and correct data types
* Export a cleaned dataset
* Generate a data cleaning report

---

## Data Cleaning Steps

### 1. Data Loading

Imported the raw Netflix dataset using Pandas and examined the dataset structure.

### 2. Missing Value Treatment

Used:

```python
df.isnull().sum()
```

Filled missing values in:

* Director
* Cast
* Country
* Rating

using appropriate replacement values.

### 3. Duplicate Removal

Removed duplicate rows using:

```python
df.drop_duplicates()
```

### 4. Column Name Standardization

Converted column names to:

* Lowercase
* Snake_case
* No extra spaces

Example:

Date Added → date_added

### 5. Text Standardization

Standardized categorical columns such as:

* Type
* Country
* Rating

to maintain consistency.

### 6. Date Formatting

Converted date columns into a consistent format:

DD-MM-YYYY

using Pandas datetime functions.

### 7. Data Validation

Verified:

* Missing values handled
* Duplicate records removed
* Correct data types assigned

### 8. Export Clean Dataset

Generated a cleaned CSV file for future analysis and dashboard development.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Google Colab
* Jupyter Notebook

---

## Project Structure

```text
Netflix-Data-Cleaning-Project/
│
├── netflix_titles.csv
├── netflix_titles_cleaned.csv
├── Netflix_Data_Cleaning.ipynb
├── Cleaning_Report.txt
├── README.md
└── requirements.txt
```

---

## Output Files

### Clean Dataset

```text
netflix_titles_cleaned.csv
```

### Cleaning Report

```text
Cleaning_Report.txt
```

---

## Key Learning Outcomes

* Data Cleaning Techniques
* Missing Value Handling
* Duplicate Removal
* Data Standardization
* Data Type Validation
* Data Quality Assessment
* Data Preparation for Analytics

---

## Future Enhancements

* Exploratory Data Analysis (EDA)
* Interactive Dashboard Development
* Content Recommendation Analysis
* Genre Trend Analysis
* Machine Learning Applications

---

## Author

Nikhil Bhoyar

B.Tech Engineering Student | Data Analytics | Data Science | Machine Learning Enthusiast

Linked-

