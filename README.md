# 🚴 Citi Bike Transportation Intelligence Dashboard

An interactive, multi-page business intelligence dashboard built from the NYC Citi Bike 2019 dataset using Apache Spark for large-scale data processing and a custom HTML/CSS/JS frontend for visualization.

## 🔗 Live Dashboard
👉 [View Dashboard](https://alialnaggar.github.io/CitiBike_Bigdata_Project/)

## 📓 Data Processing Notebook
👉 [View on Google Colab](https://colab.research.google.com/drive/1x0aJNixBuw6rezrlGRm08PUWb28ZrF0s?usp=sharing)

---

## 📊 Project Overview

This project covers the full data pipeline from raw CSV ingestion to an interactive analytics platform, processing over **1.3 million bike trips** across New York City.

### Dashboard Pages
| Page | Focus |
|------|-------|
| Executive Overview | KPI cards, hourly demand, seasonal trends, user distribution |
| Station Intelligence | Top stations, station pairs, route corridors, round-trip analysis |
| User Behavior Analytics | Age, gender, subscriber vs customer segmentation |
| Operations & Maintenance | Fleet utilization, anomaly detection, maintenance risk scoring |

---

## ⚙️ Technical Stack

| Layer | Technology |
|-------|-----------|
| Data Processing | Apache Spark (PySpark) |
| Machine Learning | Scikit-learn — Logistic Regression, Decision Tree, Random Forest |
| Visualization | Chart.js, HTML5, CSS3, Vanilla JavaScript |
| Notebook Environment | Google Colab |

---

## 🔬 Key Analysis Performed

- **Data Cleaning** — Noise flagging across 4 criteria (invalid age, missing stations, over-speed, short trips)
- **Feature Engineering** — Age groups, trip duration, distance, speed, period of day, seasonality
- **10 Analytical Queries** with business interpretations
- **13 Dashboard Queries** for visual reporting
- **ML Models** — Logistic Regression, Decision Tree, Random Forest with feature importance analysis
- **24 aggregated CSV exports** powering the dashboard

---

## 📁 Repository Structure

