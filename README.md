# E-commerce Data Cleaning with Python & Pandas

A practical data-cleaning project focused on preparing a raw e-commerce orders dataset for analysis using **Python**, **pandas**, and **Jupyter Notebook**.

## Project Objective

The goal of this project is to identify and fix common data-quality issues so the dataset becomes more reliable and analysis-ready.

## Data Quality Issues Handled

- Missing and invalid order dates
- Duplicate-record checks
- Incorrect or inconsistent data types
- Inconsistent text values in categorical columns
- Validation of calculated order totals

## Key Cleaning Steps

1. Removed 2 records with missing or invalid `Order_Date` values.
2. Checked duplicate records; final duplicate count after cleaning: **0**.
3. Converted `Order_Date` to datetime format.
4. Converted `Quantity` to integer format.
5. Standardized values in `City`, `Category`, and `Payment_Method`.
6. Recalculated order totals to validate `Total_Amount`.
7. Identified 3 total-amount mismatches and documented them rather than silently changing the source values.

## Repository Structure

| File | Description |
|---|---|
| `ecommerce_dirty_raw_dataset.csv` | Original raw dataset |
| `data_cleaning.ipynb` | Data-cleaning workflow and Python code |
| `cleaned_data.csv` | Final cleaned dataset |
| `README.md` | Project documentation |

## Tools & Skills

- Python
- pandas
- Jupyter Notebook
- Data Cleaning
- Data Validation
- Exploratory Data Preparation

## Dataset

Public practice dataset used for learning and portfolio development.

## What This Project Demonstrates

This project demonstrates my ability to inspect raw data, identify quality issues, apply structured cleaning logic, validate results, and document decisions clearly — core skills in a **Data Analyst** workflow.
