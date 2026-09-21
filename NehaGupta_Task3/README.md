# Retail Sales Data Cleaning

## Objective

The objective of this project is to clean and prepare a retail sales dataset by identifying missing values, duplicate records, inconsistent data types, and outliers.

## Dataset

The dataset used for this project is `Retail Sales Dataset.csv`.

The dataset contains 1000 rows and 16 columns related to retail sales transactions.

## Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

## Data Cleaning Steps

1. Loaded and inspected the dataset.
2. Checked for missing values.
3. Checked for duplicate rows.
4. Examined data types and descriptive statistics.
5. Detected outliers using the IQR method.
6. Inspected Quantity outliers using the IQR method.
7. Checked the consistency of Quantity, Price per Unit, and Total Amount.
8. Created a before-and-after summary of the dataset.
9. Converted the Date column from string to datetime format.
10. Saved the cleaned dataset as `Retail_Sales_Cleaned.csv`.

## Data Quality Findings

- Total rows: 1000
- Total columns: 16
- Missing values: 0
- Duplicate rows: 0
- Outliers were detected in some numeric columns using the IQR method.
- Detected outliers were retained for further analysis.

## Observation

The dataset had no missing values or duplicate records. The Date column was converted to datetime format. Some outliers were identified in the Quantity and Total Amount columns and were retained for further analysis.

## Output

 The cleaned dataset was saved as:

 `Retail_Sales_Cleaned.csv`