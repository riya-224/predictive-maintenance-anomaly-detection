# Predictive Maintenance & Anomaly Detection

# Overview
Analysed hourly sensor data (vibration, temperature) from industrial machines 
to detect anomalies and support preventive maintenance scheduling.

# What I Built
- Z-score based anomaly detection on time-series sensor data
- EWMA smoothing (span=24) to model rolling sensor trends
- Anomaly markers overlaid on time-series plots for visual fault identification
- Maintenance forecast chart tracking machines at risk monthly

# Key Findings
- Healthy Machine 37: 5 anomalies detected
- Abnormal Machine 25: 27 anomalies detected
- 15 new machines flagged at risk in January 2024, declining to 0 by March

# Tools & Libraries
Python | Pandas | NumPy | SciPy | Matplotlib

# Dataset
Source: Kaggle — [https://www.kaggle.com/datasets/ziya07/intelligent-manufacturing-dataset]
