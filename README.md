# CustomerCart Data Analysis

## 📊 Project Overview
This project focuses on analyzing online retail data to uncover key trends, customer behaviors, and actionable business insights. The analysis includes data cleaning, feature engineering, customer segmentation, sales trend analysis, and initial churn analysis. The goal is to help businesses optimize sales strategies, improve customer retention, and enhance overall operational efficiency.

## 📁 Dataset Description
The dataset consists of transactional data containing:
- **Invoice details**
- **Product descriptions**
- **Quantities sold**
- **Unit prices**
- **Invoice dates**
- **Customer IDs**

## 🧹 Data Cleaning
- **Missing Values:** Imputed missing values in 'Description' and removed entries with missing 'CustomerID'.
- **Invalid Entries:** Removed transactions with negative 'Quantity' and 'UnitPrice'.
- **Outliers:** Analyzed outliers but retained them to preserve legitimate sales data.
- **Duplicates:** Duplicate rows were not handled and may affect some summary statistics.

## 🏗️ Feature Engineering
- **TotalSales:** Calculated as `Quantity × UnitPrice`.
- **Temporal Features:** Extracted 'Month', 'Year', 'Date', 'Weekday', 'Hour', and 'Hour_Bins' from 'InvoiceDate' for time-based analysis.

## 📈 Key Findings & Visualizations

### 🔝 Top Performing Products and Countries
- **United Kingdom** leads in total sales.
- Identified top five performing countries following the UK.
- Highlighted top five products contributing most to revenue.

### 📅 Sales Trends
- **Monthly Sales:** Visualized fluctuations and seasonal patterns.
- **Hourly Sales:** Identified peak shopping hours.
- **Weekday Sales:** Analyzed day-wise sales trends.
- **Yearly Sales:** Evaluated year-over-year growth.

### 👥 Customer Segmentation (RFM Analysis)
- Segmented customers based on **Recency, Frequency,** and **Monetary Value**.
- Identified high-value and engaged customer groups.

### 📉 Customer Churn Analysis
- Defined churn as **90+ days without a purchase**.
- Used histograms to visualize churn rates and identify at-risk customers.

### 📊 User Engagement (DAU, WAU, MAU)
- Calculated and visualized **Daily, Weekly,** and **Monthly Active Users**.
- Monitored customer engagement over time.

## 🔍 Further Research & Recommendations
- **Correlation Analysis:** Explore deeper relationships between sales metrics.
- **Churn Prediction:** Apply predictive models for better retention strategies.
- **Advanced Segmentation:** Use RFM insights for targeted marketing.
- **Sales Forecasting:** Implement time series forecasting for inventory planning.

## ✅ Conclusion
This analysis serves as a strategic tool for understanding key business drivers, customer behaviors, and sales trends. By leveraging these insights, businesses can enhance decision-making, boost revenue, and strengthen customer loyalty. Future research can incorporate machine learning models for advanced forecasting and customer behavior prediction.

---

💡 *For detailed code, visualizations, and further insights, please refer to the complete analysis in this repository.*


