
# Data Preprocessing Using Python

## Overview
This project demonstrates fundamental data preprocessing techniques using Python, Pandas, NumPy, and Scikit-learn. It covers handling missing values, removing duplicate records, encoding categorical data, and scaling numerical features.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Task 1: Data Cleaning

Created a sample customer dataset and performed the following operations:

- **Handling Missing Values:** Replaced missing values in the `age` column using the median.
- **Handling Missing Categorical Values:** Replaced missing values in the `city` column using the mode.
- **Removing Duplicates:** Removed duplicate records using `drop_duplicates()`.
- **Displaying Cleaned Data:** Printed the final cleaned dataset.

## Task 2: Data Encoding and Feature Scaling

### 1. One-Hot Encoding
- Converted categorical values in the `city` column into numerical binary columns using `pd.get_dummies()`.
- Created separate columns for each city (Delhi and Mumbai).

### 2. Label Encoding
- Converted categorical values in the `gender` column into numerical labels using Scikit-learn's `LabelEncoder`.

### 3. Min-Max Scaling
- Applied `MinMaxScaler()` to the `age` and `annual_income` columns.
- Scaled numerical values into a fixed range between 0 and 1.

### 4. Standardization
- Applied `StandardScaler()` to the same numerical columns.
- Transformed the data to have a mean of approximately 0 and a standard deviation of approximately 1.

## Libraries Used

```python
import pandas as pd
import numpy as np
from sklearn.preprocessing import LabelEncoder
from sklearn.preprocessing import MinMaxScaler, StandardScaler
```

## Dataset Features

| Column | Description |
|---|---|
| customer_id | Unique customer identifier |
| age | Age of the customer |
| city | Customer's city |
| gender | Customer's gender |
| annual_income | Annual income of the customer |

## Key Learnings

- Understanding and handling missing data.
- Identifying and removing duplicate records.
- Converting categorical data into numerical representations.
- Understanding One-Hot Encoding and Label Encoding.
- Applying Min-Max Scaling and Standardization.
- Using Pandas and Scikit-learn for data preprocessing.

## Conclusion

This assignment provided practical experience with essential data preprocessing techniques. These techniques help prepare raw datasets for further analysis and machine learning applications by improving data quality and ensuring that numerical and categorical features are represented appropriately.
