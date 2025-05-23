# 📈 Hardware & Tools Sales Forecasting – 15-Year Time Series Modeling (2005–2020)

A complete forecasting pipeline developed as part of a graduate-level project in Business Analytics. This solo project involved preparing and analyzing 15 years of monthly sales data in the U.S. hardware and tools industry, from September 2005 through August 2020, and generating a 12-month forecast (September 2020–August 2021) using multiple regression models in Excel.

This work showcases end-to-end capabilities in time series preparation, model selection, error analysis, and executive communication of forecast insights.

---

## 🎯 Objective

To analyze 15 years of sales data and forecast monthly hardware and tools sales for the upcoming year, providing accurate input for supply chain planning, inventory management, and strategic decision-making.

Key project goals:
- Identify trends and seasonality in historical data
- Evaluate and compare multiple forecasting models
- Select the best-fit model based on statistical accuracy
- Generate a forecast for the next 12 months (Sep 2020–Aug 2021)
- Present insights in a format useful for operational leadership

---

## 🧾 Project Scope

**Raw Data Source**:  
Monthly U.S. hardware and tools sales figures (in millions), from **Sep 2005 to Aug 2020**, spanning 180 observations.

**Key Tasks**:
- Transpose and clean raw Excel files across multiple years
- Create unified input sheets for analysis
- Build dummy variables and period indexes
- Construct seasonal factors using moving average ratios
- Run and compare:
  - Linear Regression  
  - Exponential Regression  
  - Quadratic Regression  
  - All of the above with dummy variables  
  - Deseasonalized versions using seasonal index adjustment

**Model Selection Criteria**:
- Adjusted R²  
- Residual analysis  
- RMSE (Root Mean Squared Error)  
- Visual fit (actual vs forecasted)

**Final Model Used**:
> **Quadratic Regression with Dummy Variables**  
> Achieved an **Adjusted R² of 91.1%**, capturing both trend curvature and monthly seasonality.

---

## 📁 Project Structure

 Transposed Original Data/ # Manually cleaned and transposed raw data
├── Input Sheet/ # Core data with period, year, month, dummy vars
├── Seasonal Factors Sheet/ # Moving averages, ratio-to-MA, seasonal indexes
├── Seasonal Input Sheet/ # Sales with applied seasonal factors
├── Linear Regression.xlsx
├── Exponential Regression.xlsx
├── FINAL FORECAST (Quad w Dumm).xlsx
├── LINE GRAPH/ # Combined line chart for historical + forecast
└── Executive Summary.docx # Written analysis for a hypothetical executive


---

## 🛠️ Tools Used

- 📊 **Microsoft Excel** – Primary tool for all data transformation, modeling, and visualization  
- 📈 **Data Analysis Toolpak (Excel)** – For regression modeling (linear, exponential, quadratic)  
- 🧠 **Custom Dummy Variables** – For capturing monthly seasonality  
- 📉 **Line Graphs** – For visual validation of model performance  
- 📄 **Microsoft Word** – For composing the executive forecast summary  

---

## 📈 Skills Demonstrated

- Time Series Forecasting (Linear, Exponential, Quadratic, Dummy-enhanced)  
- Deseasonalization using moving average and seasonal index  
- Regression diagnostics (Adjusted R², RMSE)  
- Data cleaning and transformation in Excel  
- Business storytelling and reporting  
- Model selection based on interpretability and statistical soundness  

---

## 📊 Final Deliverable

The forecasted sales for Sep 2020–Aug 2021 (in millions) are embedded in the `FINAL FORECAST (Quad w Dumm)` Excel sheet. The model is expected to support supply chain and finance teams in accurate planning.

See the `LINE GRAPH` tab for a visual comparison of actual and projected sales.
