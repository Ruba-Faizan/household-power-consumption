# Task 03: Household Power Consumption Analysis

## 📌 Project Overview

This project focuses on the **Exploratory Data Analysis (EDA)** and **Time-Series Visualization** of household electrical usage. By analyzing the "Individual Household Electric Power Consumption" dataset, I identified patterns in energy demand, voltage stability, and the distribution of active power.

## 🛠️ Technical Workflow

Based on the analysis performed in the notebook:

* **Data Cleaning**: Managed non-numeric values and handled missing data points to ensure statistical accuracy.
* **Time-Series Formatting**: Converted date and time strings into a unified datetime index for chronological plotting.
* **Feature Exploration**: Analyzed the relationship between Global Active Power, Voltage, and various Sub-metering metrics.
* **Visualizations**:
* **Histograms**: Used to visualize the frequency and distribution of Global Active Power.
* **Line Charts**: Developed to track power consumption fluctuations over time.
* **Correlation Heatmaps**: Generated to identify which electrical metrics move in tandem.



## 📊 Key Findings

* **Consumption Patterns**: The global active power distribution is heavily concentrated at lower levels, with occasional high-usage spikes.
* **Metric Correlation**: There is a clear correlation between the total active power and specific sub-metering values, pinpointing major energy-consuming areas.
* **Stability**: Time-series plots of voltage show the household's electrical stability over the recorded period.

## 🧰 Libraries Used

* **Pandas**: Data manipulation and datetime indexing.
* **Matplotlib**: Static plot generation.
* **Seaborn**: Advanced statistical visualizations and heatmaps.

---
