# 💼 Investment Loan Data Analysis & Cleaning

In this notebook, I conducted a thorough exploratory data analysis (EDA) and data cleaning process on a real-world investment loan dataset. The goal was to transform a raw and complex dataset into a reliable foundation for risk modeling, credit scoring, or investment decision-making.

## 🚀 What I Accomplished

- Loaded and explored a **high-dimensional loan dataset** with over 100 columns.
- Cleaned inconsistencies, parsed dates, and removed irrelevant or highly sparse features.
- Identified and eliminated columns with excessive missing values to improve data quality.
- Parsed key datetime fields and ensured proper data types across the board.
- Created a compact, clean version of the dataset ready for financial analysis or machine learning.

## 📊 Dataset Summary

The dataset includes detailed information such as:
- **Loan issue dates**, interest rates, and amounts
- **Customer identifiers** and employment details
- **Loan purposes**, repayment terms, and statuses
- **Risk factors** like credit grades and delinquencies

## 🧠 My Workflow

1. **Data Loading & Initial Exploration**
   - Handled dtype issues using `low_memory=False`
   - Reviewed the shape and schema of the dataset
2. **Data Quality Checks**
   - Verified uniqueness of `id` and `member_id`
   - Summarized and visualized missing data
3. **Data Cleaning**
   - Dropped columns with more than 30% missing values
   - Cleaned categorical inconsistencies and whitespace
   - Converted string dates to proper datetime objects
4. **Validation**
   - Confirmed data types
   - Ensured remaining missing values were minimal and manageable

## ✅ Results

By the end of this notebook, I had transformed a noisy and incomplete dataset into a structured, analysis-ready format. It’s now suitable for:
- Risk modeling and credit scoring
- Investor profiling
- Portfolio strategy simulations

## 🛠️ Tools Used

- Python, Pandas, NumPy
- Matplotlib, Seaborn (for future visualization)
- Datetime handling and text cleaning
