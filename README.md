# Loan Amount Statistical Analysis

This project demonstrates how to perform basic statistical analysis on loan data using Python and NumPy.

## 📊 Overview

The script reads a CSV file containing loan information, extracts the loan amount column, and calculates the following statistics:

- Mean
- Median
- Standard Deviation

Missing values (`NaN`) are handled using NumPy's `nan` functions to ensure accurate calculations.

## 📁 Dataset

The script expects a CSV file named `Loan_prediction_dataset.csv` located in the same directory as the script. It assumes:

- The file contains a header row
- The 9th column (index 8) contains the loan amounts

## 🧮 Technologies Used

- Python
- NumPy
  
## 📌 Notes

- The script uses np.genfromtxt() to handle missing values gracefully.
- Make sure your dataset is clean and correctly formatted for accurate analysis.
