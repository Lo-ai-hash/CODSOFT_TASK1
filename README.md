# CODSOFT TASK 1 – Data Cleaning & Preprocessing

## Project Overview

This project focuses on cleaning and preprocessing the Titanic dataset using Python and Pandas.

The objective is to identify and handle missing values, check duplicate records, inspect inconsistent data entries, correct data types, and prepare the dataset for further analysis.

## Objectives

- Import and inspect the dataset
- Identify missing values
- Check for duplicate records
- Check categorical data for inconsistencies
- Handle missing values appropriately
- Correct data types
- Remove columns with excessive missing values
- Export the cleaned dataset as a CSV file

## Dataset

The Titanic dataset contains passenger information including:

- Passenger ID
- Survival status
- Passenger class
- Name
- Sex
- Age
- Number of siblings/spouses
- Number of parents/children
- Ticket
- Fare
- Embarked port

## Data Cleaning Performed

### 1. Missing Values

- Filled missing `Age` values using the median age.
- Filled missing `Embarked` values using the mode.
- Removed the `Cabin` column because it contained a large number of missing values.

### 2. Duplicate Records

Duplicate records were checked and no duplicate rows were found.

### 3. Inconsistent Data

Categorical columns such as `Sex` and `Embarked` were inspected for inconsistent values.

### 4. Data Type Correction

The `Sex` and `Embarked` columns were converted to the `category` data type.

## Final Dataset

After preprocessing:

- Rows: 891
- Columns: 11
- Missing values: 0
- Duplicate records: 0
- Cleaned dataset exported as `cleaned_titanic.csv`

## Technologies Used

- Python
- Pandas
- NumPy
- Google Colab
- GitHub

## Files Included

- `CODSOFT_TASK1_Data_Cleaning.ipynb` – Complete data cleaning and preprocessing notebook
- `cleaned_titanic.csv` – Cleaned dataset
- `README.md` – Project documentation

## Conclusion

The Titanic dataset was successfully cleaned and prepared for further data analysis by handling missing values, checking duplicates and inconsistencies, correcting data types, and exporting the final cleaned dataset.
