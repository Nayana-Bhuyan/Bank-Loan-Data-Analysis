Bank Loan Data Analysis

Project Overview

This project presents a comprehensive analysis of bank loan data. The primary objective is to extract actionable insights from key loan-related metrics and their changes over time. By leveraging tools like SQL, Python, Power BI, and Tableau, this analysis aims to help stakeholders make data-driven decisions, monitor the health of the loan portfolio, and identify trends that can inform future lending strategies.

Problem Statement

The bank needs a clear and consolidated view of its loan portfolio to assess performance and mitigate risk. Key business questions to be answered include:
- What is the overall health of the loan portfolio (e.g., total applications, funded amount, default rates)?
- What are the characteristics of borrowers who are likely to default?
- How do key metrics like interest rates, loan amounts, and loan purposes vary across different customer segments?
- What are the month-over-month trends for loan applications and disbursements?

Tools and Technologies

Data Source: financial_loan.csv
Database/Querying: SQL (for initial data exploration and aggregation)
Data Analysis & Cleaning: Python (Pandas, NumPy)
Data Visualization:
Microsoft Power BI
Tableau
Reporting: Microsoft Excel

Key Performance Indicators (KPIs) Analyzed

The analysis focuses on several critical banking KPIs:

Total Loan Applications: The total number of loan applications received.
Month-to-Date (MTD) Applications: The number of applications received in the current month.
Total Funded Amount: The total amount of money disbursed to borrowers.
Average Loan Amount: The average amount issued per loan application.
Average Interest Rate: The average interest rate across all loans.
Loan Status Analysis: Breakdown of loans into 'Fully Paid' and 'Charged Off' (Defaulted) categories to assess risk.

Project Structure

The repository is organized by the tools used for each part of the analysis:

/data: Contains the raw dataset (financial_loan.csv).
/SQL: Includes SQL scripts used for data extraction and initial aggregation.
/Python Project: Contains the Jupyter Notebook (Bank Loan Analysis.ipynb) for data cleaning, exploratory data analysis (EDA), and in-depth analysis.
/Power BI: Includes the Power BI report file (Bank Loan Report.pbix) and related assets.
/Tableau: Includes the Tableau workbook (Bank Loan Analysis.twbx) and related assets.
/Excel: Contains the final Excel report (Bank Loan Report.xlsx).

Visualizations and Dashboards

Interactive dashboards were created to provide a dynamic view of the data.

Power BI Dashboard

The Power BI dashboard offers a high-level summary of all major KPIs, with slicers for drilling down by year, loan status, and state.

[CRUCIAL: Insert a screenshot of your Power BI dashboard here. Upload the screenshot to your GitHub repository and then link to it.]

(Your Power BI Dashboard Screenshot Here)

Tableau Dashboard

The Tableau dashboard focuses on geographical analysis and the relationship between loan purpose, interest rates, and default rates.

[CRUCIAL: Insert a screenshot of your Tableau dashboard here. Upload the screenshot to your GitHub repository and then link to it.]

(Your Tableau Dashboard Screenshot Here)

How to Use This Repository

1. Clone the repository:
git clone https://github.com/Nayana-Bhuyan/Bank-Loan-Data-Analysis.git

2. Navigate to the relevant folder based on the tool you wish to explore (e.g., cd 'Python Project').

3. To run the Python analysis, ensure you have the required libraries installed:
pip install pandas numpy matplotlib seaborn jupyter

4. Open and run the Jupyter Notebook to see the step-by-step analysis.
