# Global Superstore Data Cleaning

## Overview

This project focuses on cleaning and preprocessing the Global Superstore dataset using Python and Pandas. The objective is to prepare raw data for analysis by handling missing values, removing duplicates, converting date formats, and exporting a cleaned dataset.

## Dataset Information

* Dataset: Global Superstore Dataset
* Total Records: 51,290
* Total Columns: 24

## Tasks Performed

### 1. Data Loading

* Imported the dataset using Pandas.
* Loaded CSV file with `latin1` encoding.

### 2. Data Exploration

* Displayed the first few records using `head()`.
* Checked dataset dimensions using `shape()`.

### 3. Missing Value Handling

* Identified missing values using `isnull()`.
* Calculated missing value percentages.
* Filled missing values in the `Postal Code` column using the median value.
* Removed rows with missing critical information.

### 4. Duplicate Removal

* Checked for duplicate records.
* Removed duplicates using `drop_duplicates()`.

### 5. Date Conversion

* Converted `Order Date` and `Ship Date` columns into datetime format using `pd.to_datetime()`.

### 6. Data Export

* Saved the cleaned dataset as `cleaned_global_superstore.csv`.

## Technologies Used

* Python
* Pandas
* Google Colab 

## Files in Repository

* `Global_Superstore2.csv` – Raw dataset
* `cleaned_global_superstore.csv` – Cleaned dataset
* `task2.ipynb` – Python notebook
* `README.md` – Project documentation

## Key Outcomes

* Successfully cleaned and standardized the dataset.
* Handled missing values and duplicates.
* Converted date columns for time-series analysis.
* Generated a cleaned dataset ready for further analytics and visualization.
