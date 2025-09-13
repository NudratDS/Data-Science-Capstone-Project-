<p align="center">
  <img src="https://github.com/NudratDS/Data-Science-Capstone-Project-/blob/main/Light%20Beige%20Digital%20Marketer%20Profile%20Header%20Banner%20LinkedIn%20_20250820_123423_0003.png?raw=1" alt="Capstone Project Banner" width="100%">
</p>

# Data-Science-Capstone-Project-
End-to-end data science pipeline project
📈 Marketing Spend Optimization for Seasonal Retail Sales Using Machine Learning

Capstone Project — Marketing Data Science | Retail & E-commerce Focus

🧠 Project Summary

This project focuses on forecasting seasonal sales trends in retail products and using those insights to inform promotion planning and campaign timing. By applying time series models (Prophet) to historical retail sales data, we aim to recommend the best months for product promotions based on data-driven seasonality.

🎯 Objectives

🔍 Analyze historical retail and warehouse sales data.

📊 Forecast future monthly sales by product category (ITEM TYPE) using time series modeling.

🗓️ Identify peak sales periods to guide marketing campaign planning.

💡 Recommend seasonal promotions to maximize ROI and inventory alignment.

📁 Dataset Overview

Source: Kaggle — Retail Sales Data with Seasonal Trends & Marketing
Rows: Monthly product sales from multiple suppliers
Columns:

Column	Description
YEAR, MONTH	Time period (monthly)
SUPPLIER	Brand or distributor
ITEM CODE	Unique product identifier
ITEM DESCRIPTION	Product name
ITEM TYPE	Product category (WINE, BEER, etc.)
RETAIL SALES	Units sold in retail
RETAIL TRANSFERS	Units transferred (restocking, etc.)
WAREHOUSE SALES	Units sold via warehouse
🧪 Methods
1. 📊 Exploratory Data Analysis (EDA)

Identified seasonality and trends across ITEM TYPE

Visualized monthly patterns and YoY comparisons

2. ⏱️ Time Series Forecasting with Prophet

Trained individual forecasting models for each ITEM TYPE

Enabled yearly_seasonality to capture seasonal effects

Forecasted next 12 months of sales for each category

3. 🎯 Promotion Timing Strategy

Analyzed predicted peak months for each product category

Proposed promotional windows to align with seasonal demand

📈 Forecasting Example

🛍️ Promotion Recommendations
Item Type	Peak Months	Suggested Campaign Period
WINE	November – December	Pre-Holiday Promotions (Oct–Nov)
BEER	June – July	Summer Campaign (May–Jun)
SPIRITS	December	Holiday Push (Late Nov–Dec)
