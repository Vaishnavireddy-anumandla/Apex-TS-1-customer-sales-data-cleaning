# Customer Sales Data Cleaning Project

## Objective
To clean, transform, and prepare a raw sales dataset for analysis.

---

## Dataset Description
The dataset contains customer details and transaction records including:

- Customer demographics
- Purchase information
- Product details
- Transaction dates

---

## Data Quality Issues Identified

✔ Missing values  
✔ Duplicate records  
✔ Inconsistent date formats  
✔ Missing email entries  
✔ Need for feature engineering  

---

## Cleaning Steps Performed

1. Removed duplicate records
2. Handled missing values
   - Filled missing emails
   - Removed rows with missing Date of Birth
3. Standardized date formats
4. Created new features
   - CustomerAge from DateOfBirth
   - ProductCategory from Product
5. Generated analysis-ready dataset

---

## Tools Used

- Python
- Pandas
- CSV files

---

## How to Run

1. Install dependencies:

pip install -r requirements.txt

2. Run script:

python scripts/data_cleaning.py

---

## Project Output

✔ Cleaned dataset ready for analysis  
✔ Documented data dictionary  
✔ Reproducible cleaning pipeline  

---

