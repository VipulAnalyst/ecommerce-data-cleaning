#SWYNEX ecommerce-data-cleaning
Cleaning a raw e-commerce orders dataset (14 columns) using Python and pandas.

## Files
- ecommerce_dirty_raw_dataset.csv: original raw data
- data_cleaning.ipynb: cleaning code
- cleaned_data.csv: final cleaned dataset

## Dataset source
[Where you got the dataset, e.g. Kaggle link or "public practice dataset"]

## Issues found and changes made
1. *Missing values:* [which columns had missing values and how you handled them, e.g. filled or dropped]
2. *Invalid dates:* 2 rows had Order_Date values that could not be parsed, so I dropped them.
3. *Duplicates:* checked for duplicate records. Remaining duplicates after cleaning: 0.
4. *Data types:* [e.g. converted Order_Date to datetime, Quantity to integer]
5. *Inconsistent values:* [e.g. standardised text in City, Category or Payment_Method]
6. *Total_Amount check:* I recomputed the total from the other columns and found 3 mismatches with Total_Amount. I left these unchanged and documented them here.

## Tools
Python, pandas, Jupyter Notebook (VS Code
