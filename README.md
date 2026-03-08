# 📊 Power BI Financial Dashboard — German Company Revenue Tracker

A multi-tab Power BI financial dashboard built for a German company, tracking billing, collections, and net revenue across a 5-year period. Connected to a live **Microsoft Azure** data pipeline, the dashboard gives finance and operations teams a single source of truth for monitoring **€576K+ in total revenue**, with dynamic filters across weekly, monthly, and yearly dimensions.

---

## 🧩 Problem Statement

The company lacked a centralized, real-time view of its financial performance. Billing data, partner extraction amounts, and revenue figures were siloed — making it difficult for decision-makers to:

- Track collection efficiency
- Identify high-performing periods
- Spot revenue gaps across multiple business partners in a timely manner

---

## 🛠️ Approach

A **three-tab Power BI report** was designed, each with independent dynamic filters (weekly, monthly, yearly, and cumulative):

| Tab | Description |
|-----|-------------|
| **Billed Amount** | Tracks invoiced totals by period and partner |
| **Extracted Money** | Monitors BML vs MB partner extraction trends |
| **Revenue** | Net revenue with cumulative "Sum Till Today" view |

**Technical stack:**
- Data ingested from **Microsoft Azure** into Power BI
- **DAX measures** built for running totals, best-period highlights, and partner-level breakdowns
- **Donut + bar chart combinations** chosen to surface both proportional share and trend simultaneously

---

## 📸 Dashboard Screenshots

### Tab 1 — Billed Amount
<img width="1063" height="774" alt="Billed Amount" src="https://github.com/user-attachments/assets/3fa1a129-58cf-4833-b075-529a8988f1e9" />

### Tab 2 — Extracted Money
<img width="1072" height="827" alt="Extracted Money" src="https://github.com/user-attachments/assets/0641cd7e-642e-4441-a4cb-d1118626bc39" />

### Tab 3 — Revenue
<img width="1059" height="762" alt="Revenue Report" src="https://github.com/user-attachments/assets/40ec8354-699e-408b-bb81-b8def7c14045" />



## 📈 Business Outcomes

- Finance teams can **instantly identify best-performing periods** (e.g., September 2021 for billing; May 2021 for revenue at **€1.26M**)
- **Partner-wise extraction trends** — BML vs MB — tracked month over month
- **Cumulative "Sum Till Today" charts** give leadership a clear growth trajectory
- Enables faster, evidence-based decisions around:
  - Invoicing cycles
  - Partner performance reviews
  - Revenue forecasting

---

## 🗂️ Repository Structure
```
├── images/
│   ├── billed-amount.png
│   ├── extracted-money.png
│   └── revenue.png
├── PowerBI_Dashboard.pbix
└── README.md
```

---

## 🔗 Data Pipeline

- **Source:** Microsoft Azure
- **Tool:** Power BI Desktop / Power BI Service
- **Refresh:** Live / Scheduled (Azure-connected)

## 🔗 Live Dashboard

View the interactive dashboard on Power BI:

[![Open in Power BI](https://img.shields.io/badge/Power%20BI-View%20Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)(https://app.powerbi.com/view?r=eyJrIjoiZjYwYjY1NjctNDY5ZS00YjQ3LWJiZWItNWMxNzIzNWQ0OTBjIiwidCI6ImZlZTNiOTE2LTAxYzEtNDk4Ny1hNjQ2LWUxOTM0MzJiOWVhYSIsImMiOjl9)
