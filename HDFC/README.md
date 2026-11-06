<div align="center">

# 🏦 HDFC Bank – Financial Performance Dashboard
### *Power BI Banking Analytics & Interactive Dashboard Project*

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Preparation-blue?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Banking%20Analytics-003478?style=for-the-badge)
![Project](https://img.shields.io/badge/Project-Financial%20Analysis-1c4e9a?style=for-the-badge)

**Power BI · HDFC Bank Dashboard Project**

</div>

---

# 📋 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Objective](#-objective)
- [📦 Data Model](#-data-model)
- [✨ Features](#-features)
- [🏗️ Repository Structure](#️-repository-structure)
- [🗂️ Report Pages](#️-report-pages)
  - [💰 Page 1: Deposits vs Targets](#-page-1-deposits-vs-targets)
  - [💳 Page 2: Loan Portfolio](#-page-2-loan-portfolio)
  - [🏢 Page 3: Branch Performance](#-page-3-branch-performance)
- [🔍 Filters & Slicers](#-filters--slicers)
- [💡 Key Insights](#-key-insights)
- [🎨 Theme & Formatting](#-theme--formatting)
- [🛠️ Tools & Techniques](#️-tools--techniques)
- [🚀 How to Use This Project](#-how-to-use-this-project)
- [🎥 Video Walkthrough](#-video-walkthrough)
- [📈 Learning Outcomes](#-learning-outcomes)
- [👤 Author](#-author)

---

# 📌 Overview

The **HDFC Bank Financial Performance Dashboard** is a Microsoft Power BI project that presents banking performance through three interactive report pages. It focuses on deposit targets, loan portfolio performance and branch-level transactions.

The report contains **three pages**:

- 💰 **Deposits vs Targets**: compares actual deposits with targets and analyzes deposit growth, product mix and branch performance.
- 💳 **Loan Portfolio**: analyzes the loan book, active loans, EMI collections, outstanding loan amounts and loan status.
- 🏢 **Branch Performance**: compares branch activity, deposits, loan book, transactions and branch rankings across regions.

The dashboard uses an HDFC Bank-inspired design with a navy-blue theme, KPI cards, charts, map visuals, hierarchy tables and report navigation.

---

# 🎯 Objective

The main objective of this project is to analyze banking data and present key financial and operational metrics in an interactive Power BI report.

The project focuses on:

- Comparing actual deposits with deposit targets
- Measuring target achievement and year-over-year growth
- Analyzing deposit distribution by product type
- Reviewing deposit performance across branch hierarchies
- Understanding loan portfolio composition and outstanding amounts
- Tracking EMI collection trends and loan status
- Comparing branch transactions and average transaction value
- Identifying high-performing branches and regions
- Using filters and drill-down analysis to explore performance

---

# 📦 Data Model

The Power BI model screenshot shows the following tables and measure groups:

| Table / Group | Purpose |
|---|---|
| `Measures_1` | Measure group |
| `Measures_2` | Measure group |
| `Measures_3` | Measure group |
| `Branch_Deposit_Targets` | Branch deposit target data |
| `Dim Account` | Account dimension |
| `Dim Branch` | Branch dimension |
| `Dim Date` | Date dimension |
| `Dim Product` | Product dimension |
| `Fact Loan Repayments` | Loan repayment fact data |
| `Fact Transactions` | Transaction fact data |

The model combines dimension tables, fact tables, deposit target data and DAX measure groups to support the dashboard analysis.

**Note:** The screenshots do not show the original dataset source, file names, row counts or complete column definitions, so those details are not specified here.

---

# ✨ Features

- 💰 Deposit KPIs: Total Deposits, Deposit Target, Achievement % and YoY Deposit Growth
- 💳 Loan KPIs: Total Loan Book, Active Loans, EMI Collection and NPA %
- 🏢 Branch KPIs: Total Branches, Total Transactions, Average Transaction Value and Best Branch
- 📊 Actual Deposit vs Target monthly comparison
- 📈 Deposit trend with Year → Quarter → Month drill-down
- 🍩 Deposit distribution by product type
- 🗺️ Geographic deposit distribution across India
- 🌳 Branch hierarchy performance tables
- 🧩 Loan portfolio distribution by product
- 📊 Outstanding loan amount by product
- 📉 EMI collection trend
- 🗺️ Loan exposure by geography
- 🍩 Loan status distribution
- 📊 Deposits by branch hierarchy
- 📈 Transactions trend and transaction-type distribution
- 🎛️ Page-specific slicers and a Clear Filters control
- 📄 Three-page report with navigation between dashboards

---

# 🏗️ Repository Structure

The folder screenshots show the Power BI report, a Dataset folder and an Assets folder containing Icon and Images subfolders.

```text
📦 HDFC Bank Dashboard
│
├── 📊 HDFC Bank Dashboard.pbix   → Power BI report file
│
├── 📁 Dataset                    → Source dataset files
│
├── 📁 Assets
│   ├── 📁 Icon                   → Dashboard icons and visual assets
│   └── 📁 Images                 → Dashboard images and backgrounds
│
└── 📝 README.md                  → Project documentation
```

---

# 🗂️ Report Pages

## 💰 Page 1: Deposits vs Targets

The **Deposits vs Targets** page compares actual deposits with assigned targets and summarizes deposit performance across products, time periods, regions and branches.

### KPI Cards

| KPI | Value displayed |
|---|---:|
| 💰 Total Deposits | ₹50,046M |
| 🎯 Deposit Target | ₹4,93,210M |
| 📊 Achievement % | 110.15% |
| 📈 YoY Deposit Growth | 50.19% |

The cards also display previous-year comparisons where shown in the report.

### Visuals

| Visual | Analysis |
|---|---|
| Actual Deposit vs Target (Monthly) | Compares monthly actual deposits and targets |
| Deposit Trend (Year → Quarter → Month) | Shows deposit movement over time with drill-down |
| Deposit by Product Type | Compares Current, Salary, Savings and Fixed Deposit |
| Geographic Deposits Distribution | Maps deposit distribution across Indian cities |
| Deposit Performance by Branch Hierarchy | Shows Region, Zone, City and Branch-level deposit performance |

### Deposit Product Distribution

| Product Type | Share displayed |
|---|---:|
| Current | 25.16% |
| Salary | 24.98% |
| Savings | 24.96% |
| Fixed Deposit | 24.89% |

### Key Insights displayed on the page

- Total deposits have exceeded the target (Achievement: 110.15%).
- Current Accounts contribute the highest share (25.16%) of total deposits.
- Central region is identified as the top performer in deposit mobilization.
- HDFC Branch 5 is identified as having the highest deposit amount among all branches.

### 📸 Dashboard Screenshot

Add your Deposits vs Targets screenshot to the `Assets/Images` folder and update the image path below.

<img src="Assets/Dashboard image/Page-1.png" alt="HDFC Bank Deposits vs Targets Dashboard">

---

## 💳 Page 2: Loan Portfolio

The **Loan Portfolio** page analyzes the total loan book, active loans, EMI collection, non-performing assets, loan products and repayment status.

### KPI Cards

| KPI | Value displayed |
|---|---:|
| 💳 Total Loan Book | ₹3,75,668M |
| 🧾 Active Loans | 78K |
| 💰 EMI Collection | ₹3,827M |
| ⚠️ NPA % | 5.00% |

### Visuals

| Visual | Analysis |
|---|---|
| Loan Portfolio by Product | Compares the loan portfolio across loan products |
| Outstanding Loan Amount by Product | Compares outstanding loan amounts by product |
| EMI Collection Trend | Shows EMI collection over time with Year → Quarter → Month drill-down |
| Loan Exposure by Geography | Maps loan exposure across Indian cities |
| Loan Status Distribution | Shows Current, Delayed, NPA and Closed loan shares |
| Deposit Performance by Branch Hierarchy | Displays branch hierarchy with loan and EMI-related metrics |

### Loan Portfolio by Product

| Loan Product | Value displayed |
|---|---:|
| Business Loan | ₹75,570M |
| Vehicle Loan | ₹75,381M |
| Education Loan | ₹74,990M |
| Home Loan | ₹74,987M |
| Personal Loan | ₹74,739M |

### Loan Status Distribution

| Loan Status | Share displayed |
|---|---:|
| Current | 80.96% |
| Delayed | 10.06% |
| NPA | 5.01% |
| Closed | Not labelled in the screenshot |

### 📸 Dashboard Screenshot

Add your Loan Portfolio screenshot to the `Assets/Images` folder and update the image path below.

<img src="Assets/Dashboard image/Page-2.png" alt="HDFC Bank Loan Portfolio Dashboard">

---

## 🏢 Page 3: Branch Performance

The **Branch Performance** page provides a branch-level view of deposits, loan book, transaction activity and branch rankings across regions.

### KPI Cards

| KPI | Value displayed |
|---|---:|
| 🏢 Total Branches | 500 |
| 🔄 Total Transactions | 500K |
| 💳 Avg Transaction Value | ₹250.17K |
| 🏆 Best Branch | HDFC Branch 112 |

The Best Branch card also identifies **West Zone** and shows **147.3% target achievement**.

### Visuals

| Visual | Analysis |
|---|---|
| Branch Network Performance | Maps branch locations across India |
| Deposits by Branch Hierarchy | Compares deposits across regions |
| Transactions Trend | Shows transaction activity over time |
| Loan Status Distribution | Displays transaction types: EMI, ATM, RTGS, NEFT, Withdrawal, UPI and Deposit |
| Deposit Performance by Branch Hierarchy | Compares deposits, loan book, transactions, achievement and branch rank |

### Key Insights displayed on the page

- Total transactions have grown by **49.97%** compared to the previous year.
- **HDFC Branch 112 (West Zone)** is identified as the top-performing branch with **147.3% target achievement**.
- North region has the highest deposits among all regions.
- Transactions are spread across seven types: EMI, ATM, RTGS, NEFT, Withdrawal, UPI and Deposit.

### 📸 Dashboard Screenshot

Add your Branch Performance screenshot to the `Assets/Images` folder and update the image path below.

<img src="Assets/Dashboard image/Page-3.png" alt="HDFC Bank Branch Performance Dashboard">

---

# 🔍 Filters & Slicers

The dashboard provides page-specific filters to explore banking performance.

| Page | Available filters |
|---|---|
| Deposits vs Targets | Financial Year, Quarter, Month, Region, Zone, Branch Name, Product Type |
| Loan Portfolio | Financial Year, Quarter, Region, Zone, Branch Name, Loan Product |
| Branch Performance | Financial Year, Quarter, Region, Zone, Branch Name, Branch Type |

A **Clear Filters** control is visible on each page to reset the selected filters.

---

# 💡 Key Insights

Based on the values and key-insight text visible in the dashboard screenshots:

- 💰 The Deposits vs Targets page displays **₹50,046M** in total deposits and **110.15%** achievement.
- 📈 Deposit year-over-year growth is displayed as **50.19%**.
- 🏦 Current Accounts have the largest displayed deposit product share at **25.16%**.
- 💳 The total loan book is displayed as **₹3,75,668M**, with **78K active loans**.
- ⚠️ The displayed NPA percentage is **5.00%**.
- 🏢 The dashboard covers **500 branches** and **500K transactions**.
- 🔄 Total transactions show **49.97%** growth compared with the previous year.
- 🏆 HDFC Branch 112 in the West Zone is highlighted as the best branch, with **147.3% target achievement**.
- 🌍 The dashboard includes geographic views for deposits, loan exposure and branch network performance.

---

# 🎨 Theme & Formatting

### Design

- HDFC Bank-inspired navy-blue header and left navigation panel
- White and light-grey visual containers
- Dark-blue titles, labels and chart elements
- KPI cards with large numeric values and circular icons
- Consistent page navigation for the three report sections
- Rounded visual containers and aligned report sections
- Map visuals for geographic analysis

### Dashboard Layout

- **Deposits vs Targets:** filters and KPI cards at the top, deposit charts in the middle, branch hierarchy table and key insights below.
- **Loan Portfolio:** KPI cards at the top, loan product and EMI visuals in the middle, geography, loan status and hierarchy analysis below.
- **Branch Performance:** KPI cards at the top, branch map and performance charts in the middle, branch hierarchy table and key insights below.

---

# 🛠️ Tools & Techniques

| Tool / Feature | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard creation and data visualization |
| Power Query Editor | Data preparation and transformation |
| Data Model | Organizing fact and dimension tables |
| DAX Measures | Calculating financial and operational KPIs |
| KPI / Card Visuals | Displaying deposits, targets, loan and branch metrics |
| Column Charts | Comparing actual deposits and targets |
| Line Charts | Showing deposit, EMI and transaction trends |
| Doughnut Charts | Displaying product and loan-status distributions |
| Bar Charts | Comparing outstanding loans and regional deposits |
| Map Visuals | Showing geographic distribution across India |
| Matrix / Hierarchy Tables | Exploring region, zone, city and branch performance |
| Slicers | Filtering by year, quarter, month, region, zone and product |
| Drill-down | Exploring Year → Quarter → Month and branch hierarchies |

---

# 🚀 How to Use This Project

1. **Clone** or download this repository.
2. Open `HDFC Bank Dashboard.pbix` using **Microsoft Power BI Desktop**.
3. If Power BI displays a data-source error, open **Home → Transform data → Data source settings** and update the source paths to the dataset files on your computer.
4. Select **Refresh** to load the data.
5. Use the page navigation on the left to switch between Deposits vs Targets, Loan Portfolio and Branch Performance.
6. Select the available slicers to filter the report by financial year, quarter, month, region, zone, branch and product.
7. Use the charts and hierarchy tables to explore the detailed performance.

**Note:** The screenshots show the report and model structure but do not provide the original dataset file names or exact source paths. You may need to update the data-source settings after opening the PBIX file on another computer.

---

# 📈 Learning Outcomes

- ✅ Build a multi-page banking analytics dashboard
- ✅ Organize fact and dimension tables in a Power BI data model
- ✅ Create DAX measures for financial KPIs
- ✅ Compare actual deposits with targets
- ✅ Analyze year-over-year growth and target achievement
- ✅ Explore loan portfolio and EMI collection performance
- ✅ Analyze loan status and NPA metrics
- ✅ Compare branch performance across regions and zones
- ✅ Use maps for geographic data visualization
- ✅ Create hierarchy tables and drill-down reports
- ✅ Add slicers and clear-filter controls
- ✅ Present banking performance through interactive visual storytelling

---

# 👤 Author

<div align="center">

# Ved Dhameliya


**HDFC Bank – Financial Performance Dashboard | Power BI Project**

*Power BI · SQL · Banking Data Analysis*

---

### ⭐ Thank You For Visiting This Project ⭐

Made with ❤️ using Microsoft Power BI

</div>
