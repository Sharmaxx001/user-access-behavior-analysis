# User Access Behavior Analysis & Anomaly Detection

## 📌 Overview

This project simulates real-world enterprise access logs and performs end-to-end data analysis to detect anomalous user behavior.  
The final output is an interactive Power BI dashboard designed to mirror security analytics and SIEM-style monitoring systems.

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebooks
- Power BI
- Git & GitHub

---

## 📂 Project Workflow

1. **Synthetic Data Generation**
   - Simulated multi-day access logs with realistic office-hour behavior
2. **Data Cleaning & Feature Engineering**
   - Timestamp parsing, user roles, access patterns
3. **Exploratory Data Analysis**
   - Temporal trends, hourly activity distribution
4. **Anomaly Detection**
   - Rule-based identification of suspicious access behavior
5. **Dashboard Data Preparation**
   - Aggregated datasets for Power BI consumption
6. **Interactive Dashboard**
   - KPI cards, trend analysis, user risk ranking, anomaly breakdown

---

## 📊 Dashboard Features

- Total anomalies detected
- Users affected & high-risk users
- Daily anomalous access trend
- Hour-of-day anomaly distribution
- Anomaly type breakdown
- Top risky users by anomalous activity

---

## 🚀 How to Run

```bash
pip install -r requirements.txt

Run notebooks in order:

00_generate_data.ipynb
01_data_cleaning.ipynb
02_exploratory_analysis.ipynb
03_anomaly_detection.ipynb
05_dashboard_data_prep.ipynb


📈 Dashboard

The Power BI dashboard is built using the CSV outputs from the data/ folder.

📌 Note

This project uses synthetic data designed to reflect realistic access behavior patterns for demonstration and learning purposes.
```
