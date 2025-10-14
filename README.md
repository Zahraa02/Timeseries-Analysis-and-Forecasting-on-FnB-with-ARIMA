# 📈 Timeseries Analysis & Demand Forecasting on FnB

**![Time Series Analysis Screenshot](path/to/screenshot/dashboard.jpg)** **(Optional: Replace `path/to/screenshot/dashboard.jpg` with the actual file path and name of a dashboard screenshot in your repository, or delete this line.)**

## 🔗 VIEW THE FULL INTERACTIVE ANALYSIS REPORT

This analysis and forecasting report has been published as a static webpage using GitHub Pages.

### **👉 [CLICK HERE TO VIEW THE LIVE REPORT](https://zahraa02.github.io/Algoritma_ML_Timeseries-Analysis-Forecasting-on-FnB/)** 👈

## Introduction
This project was developed as part of a capstone project in the **Algoritma Academy Machine Learning Specialization**. The main deliverable is to build an accurate time series forecasting model to predict demand within the Food & Beverage (FnB) sector. The focus of this report is on the process of **data pre-processing**, **model development**, performance evaluation, and interpretation of the forecasting results.

## Project Requirements

**Relevant Topics:**
- R for Data Analysis
- Exploratory Data Analysis (EDA) on time-based data
- Data Wrangling and Time Series Data Cleaning
- Time Series Decomposition (Trend, Seasonality, Remainder)

**New Exploratory Topics:**
- Time Series Forecasting Models (e.g., **ARIMA**, **ETS**, or **Prophet**)
- Stationarity Testing (ADF Test)
- Forecasting Model Evaluation (Using metrics like MAPE, RMSE)
- Generating Reproducible Analysis Reports with R Markdown

## Workflow:
- **Environment Preparation** (Setting up R and necessary packages)
- **Data Preprocessing**
    - Data Cleansing & Transformation into a time series object
    - Handling Missing Values and Outliers
- **Time Series Analysis** (Decomposition and Pattern Identification)
- **Model Development & Evaluation** (Model selection, tuning, and validation)
- **Forecasting** (Predicting future demand)
- **Report Generation** (Creating the interactive HTML report using R Markdown)

## Data Summary
The data used in this project covers daily or weekly sales information (quantity or total price) within the FnB sector over a specified period. The analysis focuses on the dynamics of sales over time to find patterns that can be utilized for accurate forecasting.

Key variables analyzed:
- **`date`** / **`timestamp`**: The time indicator for the transactions.
- **`quantity_ordered`** / **`grand_total_price`**: The primary metric used as the forecast target.

*Full details on the data and model metrics are provided within the live report.*

## Dependencies
- **R**
- **R Markdown**
- `tidyverse` (for data wrangling and visualization)
- `ggplot2` (for advanced visualization)
- `fable`, `forecast`, or `Prophet` (for time series modeling)

## Final Report
The final output of this project, including the comprehensive HTML report, code, visualizations, and forecasting results, can be viewed live via the GitHub Pages link provided above.
