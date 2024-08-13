# Anomaly Detection using STL Decomposition

This repository contains code and data for anomaly detection in time series data using Seasonal and Trend decomposition using LOESS (STL). The approach involves decomposing time series data into trend, seasonal, and residual components to detect anomalies.

## Project Overview

The goal of this project is to identify anomalies in time series data, particularly focusing on data related to process monitoring. The STL decomposition method was chosen for its robustness, flexibility, and accuracy in handling complex time series data with multiple seasonal patterns.

### Key Features:
- **Data Preparation:** 
  - Conversion of DataFrame columns to numeric types for proper analysis.
  - Imputation of missing values using mean.
  - Conversion of string-formatted time columns to appropriate datetime format.
  
- **STL Decomposition:**
  - Decomposition of each time series column to extract trend, seasonal, and residual components.
  - Calculation of upper and lower bounds for each component to determine anomalies.
  
- **Anomaly Detection:**
  - Detection of anomalies by comparing actual values with computed bounds.
  - Insights derived from the analysis suggest that the majority of anomalies were related to low inlet gas temperatures, affecting overall process stability.

### Data Insights:
- The most significant anomalies occurred between Jan 2018 - Jan 2019.
- Anomalies were primarily caused by fluctuations in the Cyclone Inlet Gas Temperature, impacting the material temperature and quality in the heating process.

## Results

![image](https://github.com/user-attachments/assets/258fa774-37ca-41b9-9afe-69cb5e8d4fea)
![image](https://github.com/user-attachments/assets/a53826fa-3dcc-4d20-9485-ce3819e5f4d3)



