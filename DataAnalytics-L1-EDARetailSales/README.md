# Data Cleaning – Titanic Dataset

## Project Overview
This project demonstrates professional data cleaning techniques using Python, Pandas, and NumPy on the Titanic dataset.

## Objective
To transform a messy dataset into a clean and analysis-ready dataset by identifying and handling missing values, duplicates, inconsistent formatting, outliers, and incorrect data types.

## Technologies Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Dataset
Titanic Dataset – 891 rows and 12 columns.

## Data Cleaning Steps
1. Loaded and inspected the dataset.
2. Generated a data quality report.
3. Handled missing values using median and mode.
4. Removed the Cabin column due to excessive missing values.
5. Checked and removed duplicate records.
6. Standardized text formatting.
7. Corrected data types.
8. Detected outliers using the IQR method.
9. Retained genuine outliers.
10. Compared before and after cleaning results.

## Final Results
- Original rows: 891
- Final rows: 891
- Original columns: 12
- Final columns: 11
- Missing values after cleaning: 0
- Duplicate rows: 0
- Output file: `titanic_cleaned.csv`

## Conclusion
The Titanic dataset was successfully cleaned and transformed into an analysis-ready dataset. The cleaned data was exported as a CSV file.