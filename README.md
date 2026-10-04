# SWYNEX: E-commerce Data Cleaning
Cleaning a raw e-commerce orders dataset (14 columns) using Python and pandas.

## Files
- ecommerce_dirty_raw_dataset.csv: original raw data
- data_cleaning.ipynb: cleaning code
- cleaned_data.csv: final cleaned dataset

## Dataset source
Public practice dataset

## Issues found and changes made
1. *Missing/invalid dates:* 2 rows had a missing or invalid Order_Date. I dropped them because an order without a valid date can't be used for analysis.
2. *Duplicates:* checked for duplicate records. Remaining duplicates after cleaning: 0.
3. *Data types:* converted Order_Date to datetime and Quantity to integer.
4. *Inconsistent values:* standardised text in City, Category and Payment_Method.
5. *Total_Amount check:* I recomputed the total from the other columns and found 3 mismatches with Total_Amount. I left these unchanged and documented them here.

## Tools
Python, pandas, Jupyter Notebook (VS Code)
