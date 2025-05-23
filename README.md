# 📈 Predictive Sales Modeling – Excel Time Series Forecasting (2005–2020)

A comprehensive forecasting project developed during graduate studies in Business Analytics. This solo project covers the full time series modeling pipeline in Microsoft Excel using 15 years of monthly sales data from the U.S. hardware and tools industry. The goal was to produce a reliable 12-month forecast for supply chain and operational planning.

The repository also includes a reusable Forecasting Cheat Sheet that documents all modeling steps, formulas, and evaluation workflows. It serves as a practical reference for any future forecasting tasks involving time series and seasonal patterns in Excel.

---

## 🎯 Objective

To forecast hardware industry sales for September 2020 to August 2021 based on 15 years of historical monthly data, using multiple time series modeling techniques. The forecast will inform resource planning for materials, staffing, and budget allocation.

Project goals:
- Identify long-term trend and monthly seasonality
- Apply and compare multiple regression-based forecasting methods
- Select the most accurate model based on Adjusted R² and RMSE
- Generate and present a month-by-month forecast for operational use
- Document the modeling process for future reuse and reference

---

## 📘 Forecasting Cheat Sheet

This project includes a detailed **Forecasting Cheat Sheet**, authored to provide a repeatable Excel-based workflow for sales forecasting. It demonstrates the ability to:

- Design and implement time series regression models
- Perform deseasonalization using moving averages and seasonal indices
- Calculate and interpret error metrics (MSE, RMSE)
- Apply dummy variables for seasonality
- Select models based on visual and statistical diagnostics

It includes step-by-step setups for:
- Linear Regression
- Exponential Regression
- Quadratic Regression
- Linear Regression with Dummy Variables
- Exponential Regression with Dummy Variables
- Quadratic Regression with Dummy Variables
- Deseasonalized Linear Regression
- Deseasonalized Exponential Regression
- Deseasonalized Quadratic Regression

This cheat sheet can serve analysts, students, or professionals looking for a practical Excel-based forecasting framework.

---

## 🧾 Project Scope

**Data**: Monthly hardware and tools sales in the U.S. from September 2005 to August 2020

**Tasks**:
- Clean and organize raw Excel data into structured input format
- Generate period and date indexes
- Create dummy variables and seasonal factors
- Apply all forecasting model types
- Evaluate model fit using Adjusted R² and RMSE
- Visualize forecasted sales vs. actuals
- Deliver business-readable insights to a hypothetical operations manager

---

## 📁 Project Structure

- Transposed Original Data/ – cleaned monthly raw data (2005–2020)
- Input Sheet/ – base columns: date, sales, period, year, month
- Seasonal Factors Sheet/ – moving average and seasonal ratio calculations
- Seasonal Input Sheet/ – sales with seasonal factor assignments
- Linear Regression.xlsx
- Exponential Regression.xlsx
- Quadratic Regression.xlsx
- Linear w Dummy Variables.xlsx
- Exponential w Dummy Variables.xlsx
- Quadratic w Dummy Variables.xlsx
- Deseasonalized Linear.xlsx
- Deseasonalized Exponential.xlsx
- Deseasonalized Quadratic.xlsx
- FINAL FORECAST (Quad w Dumm).xlsx – best-fit model (Adj. R² = 91.1%)
- LINE GRAPH/ – combined line plot of actual vs forecasted values
- Executive Summary.docx – written communication for operations management
- Forecasting Cheat Sheet.docx – complete modeling guide with formulas, logic, and error evaluation

---

## 🛠️ Tools Used

- 📊 Microsoft Excel – data transformation, regression modeling, visualization
- 📈 Excel Data Analysis Toolpak – for linear, exponential, and quadratic regressions
- 🧮 Manual dummy variable creation – to capture seasonal structure
- 🧠 Visual diagnostics + Adjusted R² – to guide model selection
- 📝 Microsoft Word – for structured business reporting

---

## 💡 Skills Demonstrated

- Predictive sales modeling and time series forecasting
- Regression modeling in Excel with seasonal components
- Deseasonalization and seasonal index construction
- Residual analysis, RMSE, and model comparison
- Business report writing and operational communication
- Reusable forecasting documentation for future deployment

---

## 📊 Final Output

The 12-month forecast for Sep 2020–Aug 2021 is stored in the `FINAL FORECAST (Quad w Dumm).xlsx` file, selected based on a strong Adjusted R² of 91.1%. This forecast balances long-term trend and monthly seasonality, making it suitable for supply chain and resource planning.

The `LINE GRAPH` tab visually compares actual vs. projected values for quick executive reference.

---

