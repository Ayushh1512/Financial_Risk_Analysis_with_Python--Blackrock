# Financial_Risk_Analysis_with_Python-Blackrock
Customer Financial Behavior and Risk Analysis Report using Python for data handling.

# Project Title: Financial Risk Analysis with Python- Blackrock

# Project Overview:

You are hired as a Financial Data Analyst by Blackrock, a major global banking institution. As digital transactions rise and customers diversify their account usage, the executive team wants to uncover patterns in customer financial behavior, account performance, and transaction risks to improve customer service and minimize financial risk.

The leadership is particularly interested in understanding:

● How do customers interact with different account types (e.g., savings, current, credit)?

● What are the trends in debit vs. credit transactions across segments?

● Can we identify accounts with unusually high risk or inconsistent financial activity?

● What transaction behaviors correlate with lower account balances or overdraft incidents?

# Project Objective:

Build a complete Customer Financial Behavior and Risk Analysis Report using Python for data handling. This report should clean and consolidate Blackrock’ customer account data, uncover transaction insights, and help decision-makers align customer strategies with
usage trends and financial risk indicators.

# Dataset:

- <a href="https://github.com/Ayushh1512/Financial_Risk_Analysis_with_Python--Blackrock/blob/main/blackrock.csv">Dataset</a>

# Tasks:

## Task 1: Data Cleaning and Formatting

● Remove/treat any special characters or non-numeric entries from financial fields.

● Convert currency amounts into numerical format.

● Validate and format date columns.

● Ensure account types and transaction categories are standardized.

## Task 2: Descriptive Transactional Analysis

● Calculate monthly and yearly summaries of total credits, debits, and net transaction volume.

● Plot trends in total credits vs. debits over time.

● Identify top and bottom performing accounts based on net inflow.

● Identify and flag accounts as dormant or inactive if there is a gap of two months or more between consecutive transactions.

## Task 3: Customer Profile Building

● Group accounts by activity levels: High, Medium, Low based on transaction frequency on your analysis and rubrics. Do not forget to mention the rubric in the headings.

● Segment customers by average balance and transaction volume.

● Create profiles for:

○ High-net inflow accounts

○ High-frequency low-balance accounts

○ Accounts with negative or near-zero balances

## Task 4: Financial Risk Identification

● Track accounts with frequent large withdrawals or overdrafts.

● Calculate balance volatility using standard deviation or coefficient of variation.

● Use IQR or z-score methods to detect anomalies.

● Highlight customers with irregular or suspicious transaction behavior.

## Task 5: Visualisation

● Conduct extensive exploratory data analysis with attractive visualizations for your findings.

## Task 6: Hypothesis Testing

● Test whether high-volume transaction accounts have statistically higher average balances than low-volume accounts.

● Conduct hypothesis testing based on segmentation.

## Task 7: Video Presentation


# Code File:

- <a href="https://github.com/Ayushh1512/Financial_Risk_Analysis_with_Python--Blackrock/blob/a3b197ea955fa1bfd895400daa321aa02f77d5ae/Blackrock_Financial_Analysis.ipynb">File:</a>

# Project Presentation:

- <a href="https://github.com/Ayushh1512/Financial_Risk_Analysis_with_Python--Blackrock/blob/24e1498998a45826a10add76a37db2647c6cd821/Financial%20Risk%20Analysis%20with%20Python-Blackrock_PDF.pdf">PPT:</a>

# Visualizations:

<img width="2000" height="1125" alt="image" src="https://github.com/user-attachments/assets/983dc732-8279-4a52-b7e4-473235a504f9" />



<img width="2000" height="1125" alt="image" src="https://github.com/user-attachments/assets/ea44f775-a4fd-4cf7-9c3f-80e28e472720" />



<img width="2000" height="1125" alt="image" src="https://github.com/user-attachments/assets/ef4a2bfd-3e92-41b6-a56c-e0cda15b305d" />



<img width="2000" height="1125" alt="image" src="https://github.com/user-attachments/assets/6540cedc-f00b-4423-afbb-434b6c4eed53" />


 # Insights:
 
- All four account types (Current, Credit, Loan, Savings) cluster within a narrow ₹6K balance range (₹70K–₹76K), meaning account type is a weak differentiator of financial health.
 
- Current accounts slightly lead with ₹76K avg balance.
 
- The more meaningful distinction lies in usage patterns: Credit accounts dominate the High Net Inflow profile (top 20 accounts, threshold ₹55,894), concentrated in North and West regions.
 
- Loan accounts appear more frequently in the 15 high-frequency low-balance accounts — suggesting loan-holders are servicing debt through active debiting.
 
- The transaction mix is nearly flat across types: Withdrawal (26.8%), Transfer (26%), Payment (24.5%), Deposit (22.8%) — confirming that spending behavior is uniform across account types rather than type-specific.
 
- Debits consistently exceed credits by 3.4× in count (618 vs 182) and at least 2× in volume every single month from Jan 2023 to Jun 2024.
 
- The October 2023 debit spike (~₹2.8M) was the highest single month in the dataset. 
 
- The ANOVA-confirmed segment gap tells the segment story: Premium customers (only 5% of accounts) hold ₹38,074 more on average than Basic — a statistically proven structural divide.
 
- Standard segment accounts (72.2%) drive the bulk of raw transaction volume but at moderate per-account values. 
 
- The key trend finding: the debit-credit gap is widening in 2024 relative to 2023 base periods, suggesting balance erosion is accelerating.
