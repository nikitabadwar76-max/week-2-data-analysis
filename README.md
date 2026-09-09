# Week 2 - Data Acquisition and Preliminary Analysis

## Project Overview

This project demonstrates data acquisition, data cleaning, and preliminary exploratory data analysis using Python.

## Dataset

The Titanic dataset was selected for this analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Data Cleaning

The following preprocessing steps were performed:

- Missing Age values were handled using the median.
- Missing Embarked values were handled using the mode.
- The Cabin column was removed due to extensive missing values.
- Duplicate records were checked.
- Categorical variables were inspected for consistency.
- Potential outliers were investigated using boxplots.

## Exploratory Data Analysis

The analysis includes:

- Survival distribution
- Survival by gender
- Survival by passenger class
- Age distribution
- Fare distribution
- Age vs Fare scatter plot
- Correlation analysis

## Files

- `Week_2_Data_Acquisition_Preliminary_Analysis.ipynb` - Google Colab/Python notebook
- `Week_2_Data_Acquisition_Preliminary_Analysis_Report.docx` - Project report
- `titanic_cleaned.csv` - Cleaned dataset
