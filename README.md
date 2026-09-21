# ⚡ GridSense AI

## Smart Grid Load Forecasting & Anomaly Detection Platform

GridSense AI is an end-to-end machine learning platform designed for **electricity demand forecasting, smart-grid telemetry analytics, renewable energy analysis, and operational anomaly detection**.

The project combines **time-series feature engineering, machine learning, anomaly detection, interactive analytics, and REST API integration** into a single intelligent energy analytics platform.

---

## 🚀 Key Features

- ⚡ Hourly electricity load forecasting
- 📈 Time-series feature engineering
- 🤖 Machine learning-based demand prediction
- 🚨 Grid anomaly detection
- 🛡️ Grid frequency and voltage monitoring
- ☀️ Renewable generation analysis
- 🌡️ Weather-to-load relationship analysis
- 📊 Interactive Streamlit dashboard
- 🌐 Flask REST API
- 📋 Automated model performance evaluation
- 🔄 Chronological train/test evaluation
- 📦 Reproducible ML pipeline

---

## 🧠 Machine Learning Architecture

```text
                Smart Grid Telemetry
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
   Load Data       Weather Data      Grid Signals
        │                │                │
        └────────────────┼────────────────┘
                         ▼
                Feature Engineering
                         │
              ┌──────────┴──────────┐
              │                     │
              ▼                     ▼
      Load Forecasting       Anomaly Detection
              │                     │
              ▼                     ▼
      Future Demand          Grid Health Alerts
              │                     │
              └──────────┬──────────┘
                         ▼
                Analytics Dashboard
                         │
                         ▼
                    REST API
