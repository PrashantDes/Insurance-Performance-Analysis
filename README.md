# Shield Insurance Performance Analysis

An end-to-end Power BI analytics project evaluating portfolio performance, revenue drivers, customer demographics, policy distributions, and sales channel effectiveness for Shield Insurance.

Developed using Power BI Project (`.pbip`) format with TMDL (Tabular Model Definition Language) and JSON report definitions for full Git version control.

---

## 📌 Project Overview

This dashboard empowers leadership and business analysts to monitor key insurance metrics, evaluate month-over-month (MoM) performance, and make data-driven decisions across customer segments, distribution channels, and policy categories.

### Key Questions Answered:
* **Portfolio Health**: How is the portfolio performing overall in terms of total revenue, customer acquisition, policy count, and claim settlements?
* **Channel Performance**: Which sales modes (Offline Agent, Online App, Online Website, Offline Direct) generate the highest revenue and customer volume?
* **Customer Demographics**: Which age groups and geographic markets (cities) are driving growth, and where are the expansion opportunities?
* **Policy Distribution**: Which policies generate the highest premium revenue and customer adoption across age brackets?
* **Risk & Settlement**: What is the expected settlement exposure across different age groups, and how does it impact profitability?

---

## 🎯 Important KPIs (Key Performance Indicators)

### 1. Overall Portfolio Performance
| KPI Metric | Value | Description |
| :--- | :--- | :--- |
| **Total Revenue** | **₹989M** | Total premium income generated across the portfolio lifetime |
| **Total Customers** | **27K** | Unique insured customers onboarded |
| **Total Policies Sold** | **27K** | Total issued policies across all channels |
| **Expected Settlement Rate** | **54.1%** | Weighted portfolio expected claim settlement exposure |

### 2. Peak Month Performance (March 2023)
| Monthly KPI | Current Month (Mar 2023) | Previous Month (Feb 2023) | MoM Growth (%) |
| :--- | :--- | :--- | :--- |
| **Monthly Revenue** | **₹264M** | ₹143M | **+85.0%** 🚀 |
| **Monthly Customers** | **7,081 (~7K)** | ~4,000 | **+82.3%** 🚀 |
| **Average Daily Revenue** | **₹9M / day** | ₹5M / day | **+67.1%** |
| **Average Daily Customers** | **228 / day** | 139 / day | **+64.6%** |

---

## 📊 Dashboard Pages & Visual Walkthrough

### 1. Insurance Performance Overview (General View)
A cross-sectional operational cockpit tracking monthly trend trajectories, city-level market contributions, and customer distribution by age group.

![Insurance Performance Overview](./Insurance%20Performance%20Overview.png)

---

### 2. Sales Mode Analysis
A channel-performance deep dive breaking down customer acquisition and revenue share across distribution channels (Offline Agents, Online App, Online Website, Offline Direct).

![Sales Performance](./sales%20view.png)

---

### 3. Age Group Analysis & Risk Exposure
An actuarial and demographic segmentation evaluating policy affinity, sales channel preferences, customer volume, and expected settlement rates across age cohorts.

![Age Group Analysis](./Age%20Group%20Analysis.png)

---

### 4. Executive Insights
A high-level executive pulse highlighting core top-line metrics: total premium income, customer reach, policy count, and portfolio-level expected settlement rate.

![Executive Insights](./Executive%20Insights.png)

---

## 💡 Key Business Insights

### 1. Seasonal Growth Surge in March 2023
* **+85% Revenue Growth**: Total revenue surged from **₹143M** in February to **₹264M** in March 2023, accompanied by an **82.3% rise in customer acquisition** (from 4K to 7.08K).
* **Driver**: This steep spike aligns with the financial year-end in India (March), where customers proactively purchase life and health insurance policies for annual tax savings under Section 80C/80D.
* **Trend Profile**: Revenue and customer numbers were relatively stable between Nov 2022 and Feb 2023 before experiencing this peak, followed by normal post-fiscal consolidation in April.

### 2. Geographic Market Dominance
* **Delhi NCR & Mumbai Drive 65% of Business**:
  * **Delhi NCR** is the primary market, generating **₹109.25M (41.4%)** in revenue with **2,920 customers**.
  * **Mumbai** is the second largest, generating **₹61.32M (23.2%)** with **1,671 customers**.
* **Tier-2 & Regional Growth Potential**:
  * **Hyderabad** generated **₹43.94M (16.7%)**, **Chennai** contributed **₹27.12M (10.3%)**, and **Indore** brought in **₹22.21M (8.4%)**.
  * Indore and Chennai present significant headroom for customer acquisition and market penetration.

### 3. Sales Channel Dynamics & Omni-Channel Shift
* **Offline Agents Remain the Core Channel**:
  * Offline Agents account for **50.85% of Revenue** and **50.59% of Customer Acquisitions** (3,582 customers in Mar 2023).
* **Rapid Digital Adoption (38% Combined Share)**:
  * **Online App** captured **20.57% of Revenue** (1,389 customers), outperforming **Online Website** (**17.43% Revenue**, 1,267 customers).
  * Together, digital channels represent nearly **38% of all business**, demonstrating strong user trust in digital onboarding.
* **Offline Direct**: Represents the smallest contribution (**11.15% Revenue**, 843 customers), suggesting walk-in branch reliance is declining.

### 4. Demographics, Policy Affinity & Risk Dynamics
* **Age Group 31–40 is the Core Revenue Engine**:
  * Contributes **₹105.48M (40.0% of total revenue)** and **3,287 customers (46.4% of total base)**.
  * Balanced expected settlement rate of **53.3%**.
  * Most popular policies for this group include `POL3309HEL` (17.8%), `POL4331HEL` (15.2%), and `POL5319HEL` (15.0%).
* **Age 18–24 & 25–30 (Low-Risk, High-Margin Segments)**:
  * **18–24**: Expected settlement rate is only **37.6%**, with heavy concentration in `POL4321HEL` (44.0%) and `POL4331HEL` (20.4%).
  * **25–30**: Expected settlement rate of **46.0%**, with `POL4321HEL` (28.8%) as the primary choice.
  * *Actuarial Insight*: These cohorts have low claim ratios, making them highly profitable for the insurer.
* **Age 65+ (High-Premium, High Settlement Exposure)**:
  * Comprises only **449 customers** but generates **₹44.31M in revenue** (highest average premium per customer at ~₹98,700).
  * Has the highest expected settlement exposure at **70.6%**.
  * High adoption of senior health policies: `POL2005HEL` (29.2%) and `POL1048HEL` (16.0%).

---

## 🎯 Strategic Business Recommendations

1. **Leverage FY-End Seasonality Proactively**:
   * Launch targeted marketing and promotional campaigns starting in January/February rather than waiting for March to capture tax-saving demand early.
2. **Promote Direct-to-Consumer Digital Channels for Age 31–40**:
   * Currently, over 50% of the 31–40 cohort purchases through offline agents (1,664 vs. 633 App / 595 Web). Incentivizing app-based renewals and self-service can significantly reduce agency commission costs.
3. **Underwriting Caution on Senior Health Policies**:
   * With a 70.6% settlement rate in the 65+ age bracket, review deductibles, co-pay clauses, and premium pricing for `POL2005HEL` and `POL1048HEL` to safeguard margins.
4. **Geographic Diversification**:
   * Replicate sales strategies from Delhi NCR and Mumbai into high-potential cities like Hyderabad and Indore to reduce regional concentration risk.

---

## 🛠️ Data Model & DAX Metrics

* **Star Schema Architecture**:
  * **Fact Tables**: `fact_premiums`, `fact_settlements`
  * **Dimension Tables**: `dim_customer`, `dim_date`, `dim_policies`
* **Core DAX Measures Included**:
  * `Total Revenue` = `SUM(fact_premiums[premium])`
  * `Revenue MoM %` = Month-over-month growth percentage
  * `Total Customers` = `DISTINCTCOUNT(fact_premiums[customer_id])`
  * `Customer MoM %` = Month-over-month customer growth
  * `Expected Settlement %` = Actuarial expected claim rate
  * `Daily Average Revenue` & `Daily Average Customers`
  * Parameterized `Trend Metric` switching between Revenue and Customer trends

---

## 🚀 How to Run the Project

1. **Prerequisites**:
   * [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (supports `.pbip` format).
2. **Opening the Report**:
   * Clone this repository:
     ```bash
     git clone https://github.com/PrashantDes/Insurance-Performance-Analysis.git
     ```
   * Open `project.pbip` in Power BI Desktop.
   * Power BI Desktop automatically loads the report visuals from `project.Report` and model definitions from `project.SemanticModel`.

---

## 📁 Repository Structure

```text
├── .gitignore                                 # Git ignore configuration
├── project.pbip                               # Power BI Project entry file
├── project.Report/                            # Report layouts, pages & visual definitions
├── project.SemanticModel/                     # Semantic Model (TMDL schema & DAX measures)
├── dax_metrics_list.xlsx                      # DAX metrics documentation
├── Shield_Insurance_Dashboard_Guide_for_Mathew.docx  # Handover & executive user guide
├── Insurance Performance Overview.png         # Screenshot: General View Page
├── sales view.png                             # Screenshot: Sales Channel Performance Page
├── Age Group Analysis.png                     # Screenshot: Demographic & Risk Analysis Page
├── Executive Insights.png                     # Screenshot: Executive Overview Page
└── README.md                                  # Project documentation & insights
```

---

## 👤 Author
- **Prashant Lodhi** ([@PrashantDes](https://github.com/PrashantDes))
