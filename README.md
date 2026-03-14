# Cybersecurity Monitoring & Analysis

## ✅ Project Overview
This repository contains a Power BI–based cybersecurity monitoring and analysis project. The goal is to ingest raw security telemetry, clean and transform it, and build interactive Power BI reports that surface meaningful security insights.

## 🗂️ Repository Structure
- `Raw Data/` – Original data files as ingested from the source (unchanged).
- `Clean Data/` – Transformed/cleaned output produced via Power BI / Power Query Editor.
- `Result/` – Exported report artifacts, visuals, or exported data used for analysis.
- `Description/Description.txt` – Notes about the dataset and any additional context.

## 📦 Data Source
- **Source:** Kaggle
- **Type:** Cybersecurity-related telemetry (logs, alerts, events, etc.)
- **Notes:** The raw dataset is stored in `Raw Data/` and should be treated as the source of truth.

## 🧹 Data Cleaning (Power BI / Power Query Editor)
Data cleaning and transformation were done using Power BI Desktop's Power Query Editor. Key steps include:
- Removing duplicate and irrelevant rows
- Standardizing column names and data types (timestamps, IPs, user IDs, etc.)
- Parsing and splitting combined fields (e.g., timestamp + message)
- Filtering out noise (non-security events, malformed records)
- Enriching records (e.g., adding derived columns for analysis)

## 📊 Analysis (Power BI)
All analysis and visualization were built in Power BI Desktop. The core analysis includes:
- **Trend analysis** – tracking event volume over time (daily/weekly/monthly)
- **Anomaly detection** – identifying spikes or unusual activity patterns
- **Top sources/targets** – most active IPs, users, or systems
- **Event categorization** – breakdown by event type, severity, or category
- **Filtering and drill-through** – interactive filtering by time range, event type, and other dimensions

---

