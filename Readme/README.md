# KYC Data Quality Dashboard

A Power BI dashboard solution for validating KYC data, monitoring compliance, and supporting audit readiness.

## 📊 Features
- **Validation Engine**: Applies rule logic to fields like DOB, Email, KYC Status, and Nationality Code
- **Star Schema Model**: Central fact table with dimension tables for Clients and Rules
- **Incremental Refresh**: Uses RangeStart/RangeEnd parameters to load only new or changed records
- **Audit Tracker**: Captures validation events and client-level audit history
- **Export Interface**: Enables filtered data export for compliance teams
- **Documentation Package**: Includes ERD, SOPs, diagrams, and a full PDF snapshot of the dashboard


## 📁 Structure
- `dashboard/` – Power BI report and screenshots
- `documentation/` – Master document, appendices, diagrams
- `data/` – Source Excel file and data dictionary

## 🚀 Getting Started
1. Clone the repo
2. Open `PowerBI_Report.pbix` in Power BI Desktop
3. Connect to `KYC_Data.xlsx` via local gateway
4. Refresh and explore

## 📄 License
MIT License
# 🛡️ KYC Compliance Dashboard


