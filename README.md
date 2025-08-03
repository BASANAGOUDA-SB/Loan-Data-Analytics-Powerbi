# 📊 Loan Data Analytics Dashboard | Power BI Portfolio Project

This repository showcases a **custom-built and business-ready Power BI dashboard** designed to analyze **loan disbursement behavior, borrower segmentation, credit risk exposure**, and **default trends**. The project reflects real-world analytics scenarios often tackled by **retail banks, NBFCs, credit analysts, and fintech risk teams**.

---

## 🚀 Objective

To build a **robust, interactive dashboard** that delivers clear, actionable insights for stakeholders across the **loan lifecycle**, empowering data-driven decisions on:

- Loan default risk monitoring  
- Borrower demographic & behavioral segmentation  
- Credit score risk classification  
- Year-over-year performance tracking  
- Automated, refreshable dashboards for real-time visibility

---

## 🔍 Analytical Insights

This solution delivers a 360° analytical view across multiple loan attributes, including:

- 📈 **YOY Loan Issuance & Default Movement**  
- 📉 **Default Rate (%)** by Purpose, Education, Employment Type  
- 🧠 **Credit Score Binning Logic** – From Very Low to High tiers  
- 👥 **Demographic Distribution** – Age Group & Marital Status patterns  
- 🔍 **Decomposition Tree Analysis** – Interactive drilldown of default drivers  
- 🧾 **Dynamic KPI Cards** – Total Loans, Defaults, Credit Score Avg., Default %

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Visual development & dashboard design |
| **DAX** | Calculated columns, YOY logic, default segmentation |
| **SQL (T-SQL)** | Backend modeling & data validation |
| **Power Query** | ETL pipeline: cleanup, joins, type transformations |
| **Power BI Dataflows** | Scheduled & Incremental Refresh support |

---

## 📊 Visual Elements Breakdown

| Component | Description |
|-----------|-------------|
| 📌 Donut Charts | Segment loan amount by Age and Marital Status |
| 📌 Clustered Column Chart | Compare Education vs Loan Distribution |
| 📌 Decomposition Tree | Explore root causes of default behavior |
| 📌 Line/Bar Charts | Track YOY trends in loan issuance & defaults |
| 📌 Slicers | Filter data by Year, Purpose, Education, etc. |
| 📌 KPI Cards | Live metrics: Total Loan Count, Default %, Avg Credit Score |

---

## 📁 Project Structure

```plaintext
Loan-Data-Analytics/
├── README.md
├── Loan Data Analysis.pbix          # Power BI project file
├── Screenshots/                     # Dashboard preview images
│   ├── dashboard-1.png
│   ├── dashboard-2.png
│   └── dashboard-3.png
└── Data/ (optional)
    └── loan_data.csv                # Raw or pre-processed dataset
