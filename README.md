# 🤖 FnB Visitor Traffic Forecasting with Time Series Analysis  

A machine learning project that applies **time series forecasting** to predict hourly visitor traffic across **dine-in, delivery, and takeaway** services, built using **Python, Pandas, and Scikit-Learn**.  


## 🚀 Overview  
The **FnB Visitor Traffic Forecasting** project was developed to analyze and predict hourly visitor patterns for food and beverage services. Its main goal is to **forecast visitor demand** for the next 7 days to support **resource allocation** and **operational planning**.  

This project focuses on:  
- 🧹 **Data Preparation** → Handling missing values, aggregating transactions, and ensuring time consistency.  
- 📊 **Exploratory Analysis** → Identifying trends, seasonality, and hourly visitor patterns.  
- 🤖 **Model Development** → Building and comparing forecasting models such as ARIMA, TBATS, and Holt-Winters.  
- 📈 **Forecasting** → Predicting hourly visitor demand for dine-in, delivery, and takeaway segments.  
- 🧪 **Evaluation** → Assessing performance using Mean Absolute Error (MAE) and visual validation.  

## 📊 Model Comparison & Performance  

| Model | Description | Evaluation Metric (MAE) | Result |
|--------|--------------|--------------------------|---------|
| **ARIMA** | Autoregressive Integrated Moving Average | < 6 | ✅ Best Performing |
| **TBATS** | Handles multiple seasonalities | > 6 | – |
| **Holt-Winters** | Exponential smoothing method | > 6 | – |

✅ **ARIMA achieved the highest accuracy**, earning a **perfect score (36/36)** for model selection, validation, and forecasting precision.  

## 📈 Key Insights  
- Peak visitor activity occurs during **midday and evening hours**, aligning with meal times.  
- **Weekends** show higher dine-in traffic, while **weekday evenings** record more delivery orders.  
- The **ARIMA model** effectively captures daily and weekly seasonal patterns, minimizing forecast error.  
- Forecasting demand enables **optimized staffing and inventory management**, improving overall efficiency.  

## 🧱 Project Workflow  
1. **Data Preparation**  
   - Load and clean raw transactional visitor data.  
   - Handle missing timestamps and maintain hourly consistency.  
2. **Exploratory Data Analysis (EDA)**  
   - Visualize trends, seasonality, and anomalies.  
   - Compare patterns across dine-in, delivery, and takeaway.  
3. **Model Development**  
   - Implement ARIMA, Holt-Winters, and TBATS models.  
   - Perform parameter tuning and cross-validation.  
4. **Model Evaluation**  
   - Compare model MAE and plot actual vs. predicted values.  
   - Select the best-performing model (ARIMA).  
5. **Forecasting & Visualization**  
   - Forecast hourly visitor traffic for the next 7 days.  
   - Visualize and interpret the forecast results.  

## 🧠 Technical Stack  
- **Language:** R  
- **Libraries:** forecast, tseries, ggplot2, dplyr, lubridate  
- **Techniques:** Time Series Forecasting (ARIMA, Holt-Winters, TBATS), Seasonal Decomposition, Model Evaluation (MAE)  
- **Environment:** RStudio / R Markdown

## 💡 Why This Matters  
Accurate visitor demand forecasting helps **FnB businesses** make informed decisions about **staffing, inventory, and operations**, reducing waste and optimizing resource allocation.  

This project demonstrates how **time series modeling** transforms raw transactional data into **actionable business insights** that directly enhance operational planning.  

## 📜 Results Summary  
- ✅ **Best Model:** ARIMA (MAE < 6)  
- 📆 **Forecast Horizon:** 7 days (hourly)  
- 🏆 **Score:** 36/36 for forecasting accuracy and model evaluation  
- 🎯 **Impact:** Enables proactive resource planning and efficient operational management  

## 💻 HTML Report  
View the complete project report with code, visualizations, and forecasting results:  
[FnB Time Series Forecasting Report](https://zahraa02.github.io/Timeseries-Analysis-and-Forecasting-on-FnB-with-ARIMA/)

## 👩🏻‍💻 Author  
**Zahra Nur Anisah** – Data Science Enthusiast  
Passionate about developing machine learning solutions that turn data into measurable business value.  

📧 **Email:** [zahranuranisah@gmail.com](mailto:zahranuranisah@gmail.com)  
💼 **LinkedIn:** [linkedin.com/in/zahranuranisah](https://www.linkedin.com/in/zahranuranisah)
