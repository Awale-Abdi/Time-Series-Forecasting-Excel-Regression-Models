<h1 align="center">📈 Hardware Retail Sales Forecasting – Excel Time Series Models Over 15 Years (2005–2020)</h1>

This solo forecasting project models 15 years of U.S. hardware and tools retail sales data using Excel-based time series techniques. Built as part of a graduate Business Analytics curriculum, the project walks through end-to-end modeling, from seasonal factor engineering to regression-based forecasting and business reporting.

Included is a reusable forecasting playbook that documents every methodology step in a practical, modular format for future time series modeling tasks.

---

## 🎯 Objective

To forecast monthly U.S. hardware retail sales for the 12-month period of September 2020 to August 2021 using multiple regression models. This forecast is intended to support resource planning in supply chain, staffing, and financial operations.

Key goals:
- Identify trends and monthly seasonality in historical data
- Apply and compare multiple forecasting models in Excel
- Evaluate models using Adjusted R² and RMSE
- Communicate insights clearly for operational leadership
- Provide a reusable modeling framework for future use

---

## 📘 Time Series Forecasting Playbook – Excel Models

This project includes a comprehensive Excel-based forecasting playbook authored by me. It outlines the complete process for setting up, executing, and evaluating time series models. Designed for reuse, the playbook was created with the intention of supporting future students, professionals, and teams working with Excel-based forecasting—whether in academic, operational, or business planning contexts.

It covers how to:

- Clean and prepare time-indexed sales data  
- Create period indices and seasonal dummy variables  
- Generate seasonal indices using moving averages  
- Build and evaluate multiple regression models in Excel  
- Compute error metrics (MSE, RMSE)  
- Visualize actual vs. forecasted sales  

### Models Covered:
- Linear Regression
- Exponential Regression
- Quadratic Regression
- Linear Regression with Dummy Variables
- Exponential Regression with Dummy Variables
- Quadratic Regression with Dummy Variables
- Deseasonalized Linear Regression
- Deseasonalized Exponential Regression
- Deseasonalized Quadratic Regression

This playbook demonstrates applied forecasting skills, practical regression analysis, and Excel modeling fluency — all in a single documented pipeline.

---

## 🧾 Project Scope

**Dataset**: U.S. hardware and tools retail sales data from Sep 2005 – Aug 2020 (monthly)

**Key Steps Applied**:
- Transpose and clean raw Excel sales data
- Add time-period indices and extract year/month from date
- Create seasonal dummy variables
- Calculate seasonal factors using ratio-to-MA method
- Test and compare multiple models
- Evaluate performance using RMSE and Adjusted R²
- Visualize forecasts with overlaid line graphs
- Communicate final results in an executive summary format

---

## 📁 Project Structure

- `Datasets/`  
  - `hardware_retail_sales_raw.xlsx` – unprocessed original sales data

- `Outputs/`  
  - `Hardware and Tools – Awale Abdi’s Results.xlsx` – full regression analysis + forecast  
  - `Time Series Forecasting Playbook – Excel Models.docx` – complete modeling guide  
  - `Executive Brief – Sales Forecast Summary.docx` – written stakeholder summary

---

## 🛠️ Tools Used

📊 Microsoft Excel – data modeling, regression analysis, visualization  
📈 Excel Data Analysis Toolpak – for regression modeling  
🧮 Manual dummy variable creation – to model monthly seasonality  
📉 Moving average method – for seasonal factor generation  
📝 Microsoft Word – for final documentation and reporting  

---

## 💡 Skills Demonstrated

- Predictive sales forecasting using Excel
- Time series modeling with seasonal and trend components
- Regression diagnostics: RMSE, residuals, Adjusted R²
- Dummy variable creation and deseasonalization techniques
- Visual storytelling through forecast graphs
- Business reporting for supply chain and operational use
- Documentation of reusable forecasting methodology

---

## 📊 Final Output

The final forecast (Sep 2020–Aug 2021) is provided in `FINAL FORECAST (Quad w Dumm).xlsx`, based on the top-performing model: **Quadratic Regression with Monthly Dummy Variables**, achieving an **Adjusted R² of 91.1%**.

See the `LINE GRAPH` sheet for visual comparison of actual vs. predicted values.

---
