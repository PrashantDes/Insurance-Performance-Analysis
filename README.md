# Shield Insurance Performance Analysis

An end-to-end Power BI analytics project evaluating portfolio performance, revenue drivers, customer demographics, policy distributions, and sales channel effectiveness for Shield Insurance.

Developed with Power BI Project (`.pbip`) format using TMDL (Tabular Model Definition Language) and JSON report definitions for Git version control.

---

## 📌 Project Overview

This dashboard empowers leadership and business analysts (e.g., portfolio managers) to monitor key insurance metrics, track month-over-month (MoM) performance, and make data-driven decisions across customer segments, distribution channels, and policy categories.

### Key Questions Answered:
* **Portfolio Health**: How is the portfolio performing overall in terms of total revenue, customer acquisition, policy count, and claim settlements?
* **Channel Performance**: Which sales modes (Direct Online, Direct Offline, Offline Agents, Online App) generate the highest revenue and customer volume?
* **Customer Demographics**: Which age groups and geographic markets (cities) are driving growth, and where are the expansion opportunities?
* **Policy Distribution**: Which policies generate the highest premium revenue and customer adoption?

---

## 📊 Dashboard Pages & Structure

1. **Landing / Welcome Page**:
   * Overview of project objectives, scope, and guided navigation buttons.
2. **Executive Insights**:
   * High-level executive pulse covering top-line KPIs: Total Revenue, Total Customers, Active Policies, and Settlement Exposure with MoM trend indicators.
3. **General View**:
   * Cross-sectional operational overview analyzing revenue and customer splits across cities, age demographics, and policy segments.
4. **Sales Mode View**:
   * Deep dive into sales channel efficiency, contribution shares, and growth trends across sales channels.
5. **Age Group Analysis**:
   * Demographic segmentation exploring customer behaviors, policy preferences, and risk/settlement dynamics across age brackets.

---

## 🛠️ Data Model & DAX Metrics

* **Star Schema Architecture**:
  * **Fact Tables**: `fact_premiums`, `fact_settlements`
  * **Dimension Tables**: `dim_customer`, `dim_date`, `dim_policies`
* **Key DAX Metrics Included**:
  * **Revenue**: Total Revenue, Revenue MoM %, Last Month Revenue
  * **Customers**: Total Customers, Customer MoM %
  * **Policies**: Policy Count, Policy Growth %
  * **Settlement**: Total Settlements, Expected Claim Exposure
  * **Dynamic Metrics**: Parameterized trend selection (`Trend Metric`)

---

## 🚀 How to Run the Project

1. **Prerequisites**:
   * [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (March 2024 or later recommended to support PBIP format).
2. **Opening the Report**:
   * Clone this repository:
     ```bash
     git clone <repo-url>
     ```
   * Open `project.pbip` in Power BI Desktop.
   * Power BI Desktop will automatically compile the report from `project.Report` and `project.SemanticModel`.

---

## 📁 Repository Structure

```text
├── .gitignore                                 # Git ignore configuration
├── project.pbip                               # Power BI Project entry file
├── project.Report/                            # PBIP Report layout and visual definitions
├── project.SemanticModel/                     # PBIP Semantic Model (TMDL schema and measures)
├── dax_metrics_list.xlsx                      # DAX metrics documentation
├── Shield_Insurance_Dashboard_Guide_for_Mathew.docx  # Handover & executive user guide
├── home.png / executive.png                   # Dashboard screenshots / previews
└── README.md                                  # Project documentation
```

---

## 👤 Author
- **Prashant Lodhi** ([@PrashantDes](https://github.com/PrashantDes))
