# 🛒 Walmart Retail Sales Forecasting & Business Analytics

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Scikit-learn](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green)

## 📌 Project Overview

This project presents an end-to-end Retail Sales Forecasting and Business Analytics solution using Python, Machine Learning, and Power BI.

The objective is to analyze Walmart's historical sales data, discover key business insights, forecast weekly sales, and build an interactive dashboard that supports business decision-making.

The project covers the complete data analytics workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, machine learning model development, and Power BI dashboard creation.

---

# 🎯 Problem Statement

Retail businesses generate massive amounts of sales data every week. Understanding sales patterns and accurately forecasting future demand are essential for inventory management, staffing, promotional planning, and overall business performance.

This project aims to:

- Analyze Walmart's retail sales data.
- Identify factors affecting weekly sales.
- Forecast future sales using Machine Learning.
- Build an interactive Power BI dashboard for business users.

---

# 📂 Dataset

The project uses the Walmart Retail Sales Forecasting dataset containing:

- Train Dataset
- Stores Dataset
- Features Dataset

Main Features:

- Store
- Department
- Weekly Sales
- Date
- Holiday Flag
- Temperature
- Fuel Price
- CPI
- Unemployment
- Store Type
- Store Size
- MarkDown Features

---

# ⚙️ Technologies Used

## Programming Language

- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Business Intelligence

- Microsoft Power BI

---

# 🔄 Project Workflow

### 1. Data Collection

- Imported Walmart datasets
- Merged datasets into a single dataframe

### 2. Data Cleaning

- Missing value handling
- Duplicate checking
- Data type conversion
- Feature engineering

### 3. Exploratory Data Analysis

- Sales Trend Analysis
- Monthly Sales Analysis
- Yearly Sales Analysis
- Store Performance
- Department Performance
- Store Type Analysis
- Holiday Sales Analysis
- Correlation Analysis

### 4. Machine Learning

Models Developed:

- Linear Regression
- Random Forest Regressor

Evaluation Metrics:

- MAE
- RMSE
- R² Score

---

# 📊 Dashboard Pages

## Page 1 — Executive Overview

- Total Revenue
- Average Weekly Sales
- Total Stores
- Total Departments
- Monthly Sales Trend
- Yearly Sales Trend
<img width="1321" height="746" alt="Dashboard-page_1" src="https://github.com/user-attachments/assets/284df6ec-2120-41b4-be29-cfd28969c447" />

---

## Page 2 — Store & Department Analysis

- Top 10 Stores by Revenue
- Top 10 Departments by Revenue
- Revenue by Store Type
- Average Weekly Sales by Store Size
- Interactive Slicers
<img width="1327" height="745" alt="Dashboard-page_2" src="https://github.com/user-attachments/assets/e983e45f-db76-464d-8e1d-42d986ec7c91" />


---

## Page 3 — Sales Drivers & Business Insights

- Holiday vs Non-Holiday Sales
- Promotion Impact Analysis
- Feature Importance
- Key Business Insights
<img width="1323" height="745" alt="Dashboard-page_3" src="https://github.com/user-attachments/assets/0daa2b93-980b-4d29-8666-825b41442967" />


---

## Page 4 — Sales Forecasting & Model Performance

- Model Comparison
- Performance KPIs
- Strategic Business Recommendations
- Project Summary
<img width="1325" height="742" alt="Dashboard-page_4" src="https://github.com/user-attachments/assets/6d6cad11-3e7b-4602-9b84-763a5955da23" />

---

## 🌐 Live Dashboard

👉 View the interactive Power BI Dashboard here:

https://app.powerbi.com/groups/me/reports/211f222c-1ce3-4e49-9334-9e91d64386e6/496bfd44109902736464?experience=power-bi

---

# 🤖 Machine Learning Results

| Model | Performance |
|--------|-------------|
| Linear Regression | R² = 0.09 |
| Random Forest | R² = 0.97 |

Random Forest significantly outperformed Linear Regression and provided accurate weekly sales predictions.

---

# 💡 Key Business Insights

- Department is the most influential factor affecting weekly sales.
- Larger stores generally generate higher revenue.
- Store performance varies significantly across locations.
- Holiday periods have a relatively small impact on overall sales.
- Weekly sales patterns play an important role in forecasting.
- Random Forest provides highly accurate sales predictions.

---

# 📈 Business Recommendations

- Prioritize inventory for high-performing departments.
- Allocate resources based on store size and demand.
- Use weekly forecasts for inventory and workforce planning.
- Focus on operational improvements rather than external economic factors.
- Deploy the Random Forest model for retail sales forecasting.
