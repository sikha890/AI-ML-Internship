# Task 1: Data Cleaning & Preprocessing

## Dataset
Titanic Dataset

## Objective
Clean and prepare raw data for machine learning.

## Steps Performed

1. Loaded and explored the Titanic dataset.
2. Inspected the dataset structure and data types.
3. Checked for missing values.
4. Filled missing Age values using the median.
5. Filled missing Embarked values using the mode.
6. Removed the Cabin column because it contained many missing values.
7. Encoded the Sex column into numerical values.
8. Applied one-hot encoding to the Embarked column.
9. Removed unnecessary Name and Ticket columns.
10. Standardized numerical features using StandardScaler.
11. Detected outliers using the IQR method.
12. Visualized outliers using boxplots.
13. Removed detected outliers.
14. Performed final validation of the cleaned dataset.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Files

- `data_preprocessing.ipynb` - Data cleaning and preprocessing notebook
- `Titanic-Dataset.csv` - Titanic dataset

## Result

The Titanic dataset was cleaned, processed, encoded, scaled, and prepared for machine learning.