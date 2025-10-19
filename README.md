# Fintech Transactions Data Cleaning and Preprocessing with Python
## Project Overview

This project demonstrates how raw, messy fintech transaction data was cleaned and prepared for analysis using Python’s Pandas library.
It simulates real-world data wrangling tasks commonly performed by data analysts — including handling missing values, correcting data types, removing unwanted characters, and structuring datasets for SQL querying and Tableau visualization.

## Data Cleaning Steps
1. Loaded raw data with missing and messy entries.
2. Removed unwanted symbols such as ``` ₦, %, ?, @, /.```
3. Converted date formats to ```datetime```.
4. Handled missing values using forward/backward fill for date-related fields.
5. Standardized text cases and stripped whitespace.
6. Converted data types ``` (numeric, categorical, datetime)```.
7. Saved the cleaned dataset as ```fintech_clean.csv for use in``` ```SQL``` and Tableau.

## Tools Used
- Python ```(Pandas, NumPy, Datetime, Regex, Seaborn, Matplotlib)```
- Jupyter Notebook

Results & Next Steps
- The cleaned dataset is ready for exploratory data analysis (EDA) in ```SQL```.
- It can be imported into ```MySQL``` or visualized in Tableau for performance trends, loan behavior, and customer insights

## Author
**Emudiaga Rukevwe Ericson**
_Data Analyst | SQL • Python • Tableau | Nigeria_
