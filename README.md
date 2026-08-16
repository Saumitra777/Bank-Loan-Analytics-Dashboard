# 🏦 Bank Loan Analytics Dashboard

An interactive *Power BI analytics* dashboard designed to analyze bank loan applications, funding, repayments, loan quality, customer financial characteristics, and portfolio performance. The dashboard transforms loan-level data into actionable KPIs and visual insights to help understand lending trends, loan performance, risk indicators, and customer segments.

## 📌 Project Purpose

The Bank Loan Analytics Dashboard provides a consolidated view of **38,576 loan applications**, helping users analyze loan activity, funded amounts, repayments, interest rates, DTI ratios, loan purposes, customer home ownership, and loan performance.

The dashboard is designed to answer key business questions such as:

* How are loan applications changing over time?
* How much has been funded and how much has been received?
* What percentage of applications are classified as good vs. bad loans?
* Which loan purposes generate the highest application volumes?
* How do loan terms and customer home ownership affect applications?
* How do interest rates and DTI ratios vary by loan status?
* Which states contribute the highest number of applications?
* How does loan performance differ between Fully Paid, Current, and Charged Off loans?

---

## 🛠️ Tech Stack

The dashboard was developed using:

* 📊 **Power BI Desktop** – Dashboard development, interactive visualizations, KPI reporting, and analysis.
* 🔄 **Power Query** – Data loading, transformation, data-type handling, and preparation.
* 🧠 **DAX** – Created calculated measures for loan applications, funded amount, amount received, average interest rate, average DTI, and good/bad loan analysis.
* 🗂️ **Data Modeling** – Structured the financial loan dataset and date dimensions for time-based analysis.
* 📈 **Data Visualization** – KPI cards, line charts, bar charts, donut charts, treemap, map visualization, and interactive slicers.
* 📁 **File Formats** – `.pbix/.pbit` for Power BI development and `.png` for dashboard previews.

---

## 📂 Data Source

The dashboard uses a **financial loan dataset** containing loan application and customer-level financial information.

The primary dataset includes attributes such as:

* Loan ID
* Issue Date
* Loan Purpose
* Verification Status
* Loan Grade & Sub-Grade
* Home Ownership
* Address State
* Loan Status
* Employment Length
* Annual Income
* Debt-to-Income (DTI) Ratio
* Interest Rate
* Installment
* Loan Amount
* Total Payment
* Payment and credit-related dates
* Good vs. Bad Loan classification

The dataset contains **38,576 loan applications** used for portfolio-level analysis.

---

# 📊 Dashboard Features & Highlights

## 🔹 Business Problem

Banks and lending organizations manage large volumes of loan applications and financial transactions. Raw loan-level data can make it difficult to quickly understand application trends, funding performance, repayment behavior, loan quality, and customer risk characteristics.

This dashboard converts the underlying loan data into an interactive analytical report that allows users to monitor portfolio performance and investigate lending trends through different dimensions.

---

## 🎯 Goal of the Dashboard

The primary goal is to provide an interactive analytical solution that:

* Monitors overall loan application performance.
* Tracks funded and received amounts.
* Evaluates good vs. bad loan performance.
* Identifies monthly application trends.
* Analyzes loan purpose and customer segments.
* Compares loan performance by loan status.
* Monitors interest rate and DTI patterns.
* Enables users to drill into the portfolio using interactive filters.

---

# 📈 Dashboard Walkthrough

## 1. Executive KPI Summary

The dashboard provides high-level KPIs including:

* **Total Loan Applications:** 38,576
* **Total Funded Amount:** $435.8M
* **Total Amount Received:** $473.1M
* **Average Interest Rate:** 12.05%
* **Average DTI Ratio:** 13.33%

These KPIs provide an immediate overview of the loan portfolio.

---

## 2. Monthly Loan Application Trend

A monthly line chart tracks loan application volume throughout the year.

The visualization helps identify:

* Application growth patterns
* High and low application periods
* Monthly demand trends
* Overall changes in loan activity

Applications increase from approximately **2.3K in January to 4.3K in December**, providing a clear view of the upward application trend across the year.

---

## 3. Loan Applications by State

A geographic map visualizes loan application distribution across U.S. states.

This enables users to identify:

* Geographic concentration of applications
* High-volume states
* Regional lending patterns
* Potential differences in market demand

---

## 4. Loan Applications by Term

A donut chart compares loan applications across different repayment terms.

The dashboard shows:

* **60-month loans:** 73.2%
* **36-month loans:** 26.8%

This provides insight into customer preference for different repayment periods.

---

## 5. Loan Applications by Home Ownership

A horizontal bar chart compares applications across customer home-ownership categories.

The dashboard highlights categories such as:

* Rent
* Mortgage
* Own
* Other
* None

This helps analyze the relationship between customer housing status and loan demand.

---

## 6. Loan Applications by Purpose

A treemap visualizes loan applications across different purposes, including:

* Debt Consolidation
* Credit Card
* Major Purchase
* Small Business
* Home Improvement
* Car
* Medical
* Moving
* Education
* Wedding
* Vacation
* Renewable Energy
* Other

This allows users to identify the major drivers of loan demand.

---

# 🔍 Loan Quality Analysis

## Good vs. Bad Loan Performance

The Overview page separates the portfolio into **Good Loan** and **Bad Loan** applications.

### Good Loans

* **33,243 applications**
* **86.18% of total applications**
* **$370.2M funded amount**
* **$435.8M amount received**

### Bad Loans

* **5,333 applications**
* **13.82% of total applications**
* **$65.5M funded amount**
* **$37.3M amount received**

This analysis provides a high-level view of portfolio quality and helps identify the proportion of loans requiring closer risk monitoring.

---

# 💰 Loan Status Analysis

The dashboard compares:

* **Fully Paid**
* **Charged Off**
* **Current**

across multiple financial measures.

### Funded Amount vs. Amount Received

The visualization compares funded amounts with total amounts received for each loan status, helping evaluate repayment performance.

### Loan Applications

Loan application volumes are compared across different loan statuses to understand portfolio composition.

### Average Interest Rate

The dashboard compares interest rates across loan statuses, helping identify differences in pricing between Current, Charged Off, and Fully Paid loans.

### Average DTI Ratio

DTI ratios are compared across loan statuses to evaluate differences in borrower financial characteristics.

---

# 🎛️ Interactive Features

The dashboard includes interactive filtering capabilities that allow users to analyze the portfolio by loan purpose, including:

* Car
* Credit Card
* Debt Consolidation
* Educational
* Home Improvement
* House
* Major Purchase
* Medical
* Moving
* Other
* Renewable Energy
* Small Business
* Vacation
* Wedding

Users can dynamically filter the dashboard and analyze how different loan purposes affect portfolio KPIs and visualizations.

---

# 🧠 DAX Measures

The project uses DAX measures to calculate important portfolio KPIs, including:

* Total Loan Applications
* Total Funded Amount
* Total Amount Received
* Average Interest Rate
* Average DTI Ratio
* Good Loan Applications
* Good Loan %
* Bad Loan Applications
* Bad Loan %

These measures enable dynamic KPI calculations across dashboard filters and visualizations.

---

# 💡 Key Business Insights

The dashboard provides several analytical insights:

* Loan applications show an overall upward trend across the analyzed period.
* The majority of applications are associated with **60-month loan terms**.
* **Rent and mortgage** customers represent the largest home-ownership segments.
* **Debt consolidation** represents the largest loan-purpose category.
* Good loans account for approximately **86.18%** of applications, while bad loans account for **13.82%**.
* Fully Paid loans represent the largest portion of the analyzed loan portfolio.
* Interest rates and DTI ratios vary across different loan statuses, providing additional indicators for portfolio analysis.

---

# 🎯 Business Impact

This dashboard can support banking and lending teams by providing:

**Portfolio Monitoring:**
Quick visibility into application volumes, funded amounts, repayments, and loan status.

**Risk Analysis:**
Good vs. bad loan analysis helps identify portfolio-quality patterns.

**Customer Segmentation:**
Loan purpose, home ownership, geography, and financial characteristics can be analyzed to understand borrower segments.

**Performance Tracking:**
KPIs such as application volume, funded amount, received amount, interest rate, and DTI provide a consolidated view of portfolio performance.

**Decision Support:**
Interactive filtering and drill-down analysis allow stakeholders to investigate trends and identify areas requiring further analysis.

---

## 📁 Project Structure

```text
Bank-Loan-Analytics-Dashboard/
│
├── Bank Loan Analytics Dashboard.pbit
├── README.md
│
└── Dashboard Preview/
    ├── Summary.png
    └── Overview.png
```

## 👨‍💻 Project Objective

This project demonstrates practical skills in **Power BI, Power Query, DAX, data modeling, KPI development, data visualization, and business-oriented data analysis**, with a focus on converting raw financial data into an interactive decision-support dashboard.

## Screenshots / Demos
Show what the dashboard looks like. Example: (https://github.com/Saumitra777/Bank-Loan-Analytics-Dashboard/edit/main/README.md)

