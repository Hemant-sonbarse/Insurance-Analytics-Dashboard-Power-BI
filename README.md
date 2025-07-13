# Retail Insurance Power BI Project 📊

This is a complete end-to-end Power BI project created for an insurance company to analyze customer data, policy trends, claim summaries, and customer feedback using various advanced Power BI functionalities.

## 🚀 Project Highlights

✅ Integrated Data from SQL + Excel  
✅ Power Query & Data Transformation  
✅ Role-Level Security (RLS)  
✅ Scheduled Data Refresh (via Gateway)  
✅ AI-Based Sentiment Scoring  
✅ Word Cloud using AppSource Visual  
✅ Drillthrough Functionality  
✅ Responsive Dashboard Shared via Power BI Service

---

## 📁 Folder Structure

| Folder              | Description                                                  |
|---------------------|--------------------------------------------------------------|
| `Data/`             | Raw data files used in the report (e.g., `.sql`, `.xlsx`)    |
| `PBIX_Files/`       | Final Power BI report file (`.pbix`)                         |
| `Screenshots/`      | Captures of dashboards, RLS settings, refresh setup, etc.    |
| `README.md`         | This file — project summary and explanation                  |
| `.gitignore`        | File to exclude system or temporary files from Git           |

---

## 📂 Files Included

| File                        | Description                                 |
|-----------------------------|---------------------------------------------|
| `Insurance_Analysis_Report.pbix` | Complete Power BI file                |
| `insurance_data.sql`             | SQL script used for core dataset     |
| `customer_feedback.xlsx`         | Excel file with feedback entries     |
| `Screenshots/`                   | Visual outputs and configuration proofs |

---

## 🔍 Key Functionalities Covered

### 📦 1. Data Sources
- **Microsoft SQL Server** – Used for policy, customer, and claim data.
- **Excel Workbook** – Used for customer feedback data.
- Integrated both sources in Power BI Desktop.

### 🧹 2. Data Cleaning & Transformation
- Applied transformations in **Power Query Editor**
- Added conditional columns for sentiment buckets
- Parsed & shaped text data for analysis

### 📈 3. Visualizations
- KPI Cards for claim amount & policyholder stats
- Bar charts for policy & claim breakdown
- Drillthrough-enabled report pages
- Word Cloud for frequent feedback terms
- Table showing full feedback details

### 🧠 4. Text Analytics
- Performed **Sentiment Analysis** using Power BI's Text Analytics (Cognitive Services)
- Created a sentiment score column and categorized feedback as:
  - `Excellent` (≥ 0.8)
  - `Good` (0.6–0.8)
  - `Needs Improvement` (< 0.6)
    
### 🔒 5. Row-Level Security (RLS)
- Configured roles like:
  - **Health Role**
  - **Travel Role**

### 🔁 6. Scheduled Refresh
- SQL Server data refreshed daily using **Power BI Gateway**
- History of successful refreshes maintained in Power BI Service

### 🧾 7. Dashboard
- Created a one-page dashboard by pinning visuals from multiple report pages
- Used for executive-level summaries
