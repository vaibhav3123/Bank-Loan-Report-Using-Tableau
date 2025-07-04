🏦 Bank Loan Report Dashboard (SQL Server + Tableau)

## 📌 Overview

📌 Overview
This project presents an interactive Bank Loan Analysis Dashboard built using Microsoft SQL Server for data processing and Tableau for visualization. It offers a clear and actionable view of loan performance, borrower segmentation, and financial KPIs. The dashboard is designed to help financial institutions assess risk, monitor trends, and make data-driven decisions.
The report is split into two main sections:

Summary View: High-level KPIs and loan quality insights

Overview Page: Trend, geographic, and demographic analysis


## 🚀 Key Metrics

* **Total Loan Applications:** 38.6K
* **Total Funded Amount:** $435.8M
* **Total Amount Received:** $473.1M
* **Avg Interest Rate:** 12.0%
* **Avg Debt-to-Income (DTI):** 13.2%
* **Good Loans Issued:** 86.2%
* **Bad Loans Issued:** 13.8%

🧾 Data Processing
All required metrics and breakdowns were calculated using Microsoft SQL Server. The SQL queries were designed to handle the following:

✅ **Monthly and Total KPIs**: Including total loan applications, funded amount, and amount received
📊 **Average Calculations**: For interest rate and debt-to-income (DTI) ratio
🔍 **Loan Classification**: Segregation of good loans (Fully Paid / Current) and bad loans (Charged Off)
📋 **Loan Status Groupings**: Aggregated by repayment status (e.g., Fully Paid, Current, Charged Off)
🧩 **Segment Analysis**: Based on geography (state), term duration, employment length, loan purpose, and home ownership
These processed results were connected directly to Tableau to build interactive, filter-enabled dashboards for end-user analysis.


## 📊 Visualizations & Insights

### 1️⃣ Donut Charts – Good vs Bad Loans

* Visual breakdown of loan quality
* Highlights distribution of loan applications and their repayment outcomes

### 2️⃣ KPI Cards – Performance Summary

* Displays real-time metrics including application count, funded amount, amount received, average interest rate, and DTI

### 3️⃣ Loan Status Table

* Segregates loans as Fully Paid, Charged Off, and Current
* Includes total applications, funded amounts, amount received, and month-to-date metrics

### 4️⃣ Line Chart – Monthly Loan Application Trends

* Identifies seasonal changes in loan applications across the year

### 5️⃣ Bar Charts – Employment Length & Purpose

* Analyzes loan applicant employment duration and reason for loan
* Reveals dominant job tenure and top loan purposes like debt consolidation

### 6️⃣ Pie Chart – Loan Terms

* Compares 36-month vs 60-month loans
* Shows user preference toward long-term loans (60 months = 77.58%)

### 7️⃣ Map – State-wise Applications

* Visualizes geographic distribution of loans across the U.S.

### 8️⃣ Treemap – Home Ownership

* Categorizes loan applications by RENT vs MORTGAGE ownership



## 🔍 Key Business Insights

✔ 86.2% of loans issued are categorized as **Good Loans**
✔ **Debt Consolidation** is the most common purpose for loan applications
✔ Applicants with **10+ years of experience** form the largest group
✔ **60-month** loan terms are highly preferred over 36 months
✔ Renters account for slightly more applications than homeowners


🛠️ Technologies Used
-**Microsoft SQL Server** – For writing queries to aggregate, filter, and clean the data
-**Tableau** – For building the interactive and user-friendly dashboards
-**MS Excel**– For initial dataset formatting



## 📈 Potential Use Cases

🔹 **Loan Risk Analysis**: Helps financial institutions identify high-risk borrowers
🔹 **Customer Segmentation**: Analyze loan behavior by employment, ownership, and purpose
🔹 **Repayment Monitoring**: Track recovery trends of good vs bad loans
🔹 **Strategic Planning**: Optimize policies based on application, funding, and repayment patterns


## 🔗 Project Links

🔹 **Live Dashboard**: [Tableau Public](https://public.tableau.com/views/BankLoanReport_17516140932180/SUMMARY?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


## 🤝 Connect with Me

📬 Open to feedback, discussions, and collaborations!
💼 **LinkedIn**: [Vaibhav Bari](https://www.linkedin.com/in/vaibhav-bari-915bb5202)
