# FinTrust Digital Bank – Week 2 Data Analysis

## Project Overview

Week 2 focuses on transforming the FinTrust Digital Bank dataset into a cleaned, analysed and business-ready data solution.

The analysis covers:

- Data quality and cleaning
- SQL business analysis
- Python exploratory data analysis
- Power BI dashboard development
- DAX measures
- Business findings and recommendations
- Documentation and validation

All FinTrust data used in this project are synthetic/fictional and are intended for educational purposes only.

---

## Business Problem

FinTrust Digital Bank wants to better understand customer behaviour and transaction activity across its digital banking ecosystem.

The Week 2 analysis focuses on identifying:

- Customer activity patterns
- Transaction volumes and values
- Transaction types
- Channel usage
- Transaction success and failure
- Customer segment behaviour
- Risk-review patterns
- Monthly transaction trends
- Data quality issues

---

## Dataset

### Customer Dataset

The customer dataset contains 1,500 customer records and 12 fields.

Key fields include:

- Customer_ID
- Customer_Name
- Age
- Gender
- City
- Customer_Segment
- Account_Type
- Tenure_Months
- Digital_Engagement_Score
- Monthly_Income_Band
- Preferred_Channel
- Account_Status

### Transaction Dataset

The transaction dataset contains 12,000 transaction records and 11 fields.

Key fields include:

- Transaction_ID
- Customer_ID
- Transaction_DateTime
- Transaction_Type
- Amount_NGN
- Channel
- Device_Type
- Location
- International_Transaction
- Transaction_Status
- Risk_Review_Flag

---

## Week 2 Activities

### 1. Data Quality and Cleaning

The datasets were reviewed for:

- Missing values
- Duplicate records
- Incorrect or inconsistent values
- Data types
- Unusual transaction amounts
- Customer/transaction relationships
- Referential integrity

Key results:

- 1,500 customer records
- 12,000 transaction records
- No duplicate customer rows
- No duplicate transaction rows
- No orphan Customer_ID values
- 96 missing Device_Type values
- 96 missing Location values
- Potential transaction amount outliers identified using the IQR method

Missing categorical values were represented as "Unknown" in the analytical copy.

Potential outliers were retained because they may represent legitimate high-value transactions.

---

## 2. SQL Analysis

SQL was used to answer business questions covering:

- Customer activity
- Transaction volume
- Transaction value
- Transaction status
- Transaction type
- Transaction channel
- Customer segments
- Risk-review patterns
- International transactions
- Monthly transaction activity

The SQL analysis contains more than eight business questions with queries, results and interpretations.

---

## 3. Python Exploratory Data Analysis

Python tools used:

- Pandas
- NumPy
- Matplotlib
- Seaborn

The Python analysis includes:

- Data quality checks
- Descriptive statistics
- Transaction KPIs
- Monthly analysis
- Channel analysis
- Transaction-type analysis
- Customer-segment analysis
- Transaction amount analysis
- Outlier analysis
- Business-focused visualisations

Seven visualisations were created as part of the exploratory analysis.

---

## 4. Power BI Dashboard

The Power BI solution focuses on transaction and customer performance.

### Main KPIs

- Total Customers
- Total Transactions
- Total Transaction Value
- Average Transaction Value
- Transaction Success Rate
- Risk Review Rate

### Dashboard Analysis

The dashboard includes analysis of:

- Customer segments
- Transaction types
- Transaction channels
- Monthly trends
- Transaction status
- Risk-review patterns
- International transactions

Slicers and filters are included to support interactive analysis.

---

## 5. Key Business Findings

### Finding 1 – Mobile App Usage

The Mobile App recorded 5,102 transactions out of 12,000 transactions.

This represents approximately 42.52% of total transaction volume.

**Business meaning:** The Mobile App is an important transaction channel and should be monitored closely when evaluating digital banking activity.

### Finding 2 – Transfer Activity

Transfer transactions were the largest transaction type with 3,549 transactions.

This represents approximately 29.58% of total transaction volume.

**Business meaning:** Transfers represent a significant component of transaction activity and should be considered when analysing transaction behaviour.

### Finding 3 – March Transaction Value

March 2026 recorded the highest total transaction value at approximately NGN 196.20 million.

**Business meaning:** Monthly transaction value should be monitored to identify changes in transaction activity over time.

### Finding 4 – Transaction Success

10,856 transactions were successful, representing approximately 90.47% of all transactions.

**Business meaning:** Transaction status analysis provides an important measure for monitoring transaction processing outcomes.

### Finding 5 – Risk Review Pattern

Transfer transactions had a synthetic Risk_Review_Flag rate of approximately 28.49%, compared with 19.60% across all transactions.

**Important:** Risk_Review_Flag is an educational/synthetic field and should not be interpreted as proof of fraud or actual banking risk.

### Finding 6 – International Transactions

480 transactions were classified as international transactions, representing 4.00% of total transactions.

**Business meaning:** International activity can be monitored separately from domestic transaction activity for analytical purposes.

---

## 6. Key Data Quality Findings

| Check | Result |
|---|---:|
| Customer records | 1,500 |
| Transaction records | 12,000 |
| Duplicate customer rows | 0 |
| Duplicate transaction rows | 0 |
| Missing Device_Type | 96 |
| Missing Location | 96 |
| Orphan Customer_IDs | 0 |
| Potential IQR outliers | 1,474 |

---

## 7. Tools Used

- Microsoft Excel
- SQL
- SQLite
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- DAX
- Power Query
- GitHub

---

## 8. Week 2 Deliverables

The Week 2 repository contains:

1. Data Quality and Cleaning Workbook
2. SQL Analysis
3. SQL Database
4. Clean Customer Dataset
5. Clean Transaction Dataset
6. Python EDA Notebook
7. Python EDA Script
8. Power BI DAX Measures
9. Power Query M Code
10. Power BI Theme
11. Power BI Build Guide
12. Business Findings
13. Week 2 Project Documentation
14. Validation Evidence

---

## 9. Limitations

The dataset is synthetic and should not be treated as real banking data.

The Risk_Review_Flag field is provided for educational analytical purposes and does not represent a confirmed fraud or risk assessment.

Potential transaction amount outliers were identified statistically but were not automatically removed because they may represent legitimate high-value transactions.

---

## 10. Week 3 Focus

Proposed Week 3 activities include:

- Further dashboard refinement
- Deeper customer segmentation
- Additional analytical insights
- Dashboard validation
- Presentation of findings
- Final documentation
- Preparation of the final project submission

---

## Project Status

**Week 2 – Completed**

The repository contains the analytical outputs, code, documentation and supporting evidence required for the Week 2 assignment.
