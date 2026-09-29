# Superstore Data Cleaning & Verification (Python)

Cleaned and verified a 9,800-row retail sales dataset using Python and pandas.

## What I did
- Converted Order Date and Ship Date from text to proper datetime format
- Checked for duplicate rows and missing values across all columns
- Verified Region, Category, Segment and Ship Mode contain only consistent values
- Checked for extra spaces in text fields
- Verified Sales values are positive with no unrealistic outliers
- Verified no order has a Ship Date earlier than its Order Date
- Identified a known data quirk: 32 Product IDs have inconsistent Product Name spellings

## Tools
Python, pandas, Google Colab

## Result
Confirmed the dataset was clean and analysis-ready, with one documented exception noted for transparency.
