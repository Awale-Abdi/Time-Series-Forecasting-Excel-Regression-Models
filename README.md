<h1 align="center">Hardware Retail Sales Forecasting – Excel Time Series Models Over 15 Years (2005–2020)</h1>

This Excel-based time series forecasting project analyzes 15 years of U.S. hardware and tools retail sales data to generate a 12-month predictive sales forecast. Completed as part of a graduate-level **Supply Chain Analytics** course, the assignment placed me in the role of a **Supply-Chain Analyst** tasked with producing a highly accurate monthly sales forecast to inform internal resource planning—materials, staffing, and financial capacity for the upcoming fiscal year.

Simulating a real-world corporate environment, the task required evaluating industry sales data (Sep 2005–Aug 2020), modeling future demand for Sep 2020–Aug 2021, and benchmarking accuracy against the actual sales. In parallel, the assignment also tested mastery of regression, seasonality, and deseasonalization concepts via randomized numerical questions and a written trend/seasonality assessment.

📊 A separate *Forecast vs. Actual Sales* validation sheet is included to compare the forecast against real 2021 Census retail sales figures. This comparison demonstrates forecast realism and business applicability using Mean Absolute Percentage Error (MAPE) and trend visualization.

The final forecast is further presented in a concise executive summary tailored for operational stakeholders, delivering clear, actionable insights. Also included is a reusable Time Series Forecasting Playbook authored to document the complete modeling workflow. It serves as both a practical forecasting guide and evidence of applied proficiency in time series forecasting techniques using Excel.

---

## 🎯 Objective

To forecast monthly U.S. hardware retail sales for the 12-month period of September 2020 to August 2021 using multiple regression models. This forecast is intended to support resource planning in supply chain, staffing, and financial operations.

Key goals:
- Identify trends and monthly seasonality in historical data  
- Apply and compare multiple forecasting models in Excel  
- Evaluate models using Adjusted R² and RMSE  
- Compare forecast to actual U.S. Census retail data  
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
- Compute error metrics (MSE, RMSE, MAPE)  
- Visualize actual vs. forecasted sales  
- Benchmark forecast performance against real-world results  

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

---

## 🧾 Project Scope

**Dataset**: U.S. hardware and tools retail sales data from Sep 2005 – Aug 2020 (monthly)

**Key Steps Applied**:
- Transpose and clean raw Excel sales data  
- Add time-period indices and extract year/month from date  
- Create seasonal dummy variables  
- Calculate seasonal factors using ratio-to-MA method  
- Test and compare multiple models  
- Evaluate performance using RMSE, Adjusted R², and MAPE  
- Visualize forecasts and trend alignment  
- Communicate results in a visual + written executive summary  

---

## 📁 Project Structure

- `Datasets/`  
  - `Hardware and Tools - Original Dataset.xlsx` – unprocessed original sales data  

- `Outputs/`  
  - `Hardware and Tools – Awale Abdi’s Results.xlsx` – full regression analysis + forecast  
  - `Forecast Vs. Actual Sales.xlsx` – comparison of predicted vs. real 2021 sales (MAPE = 9.3%)  
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
- Regression diagnostics: RMSE, residuals, Adjusted R², MAPE  
- Dummy variable creation and deseasonalization techniques  
- Real-world forecast validation using government retail data  
- Visual storytelling through comparative forecast graphs  
- Business reporting for supply chain and operational use  
- Documentation of reusable forecasting methodology  

---

## 📊 Final Output

The final forecast (Sep 2020–Aug 2021) is provided in the **FINAL FORECAST (Quad w Dumm)** sheet of the `Hardware and Tools – Awale Abdi’s Results.xlsx`, based on the top-performing model: **Quadratic Regression with Monthly Dummy Variables**, achieving an **Adjusted R² of 91.1%**.

Forecast validation against 2021 U.S. Census data is included in the `Forecast Vs. Actual Sales.xlsx`, with a **Mean Absolute Percentage Error of 9.3%**, showing strong alignment with real-world demand.

---

### **Contact Me**

For questions or collaboration, reach out via:

- Awaleiabdi@outlook.com  
- [LinkedIn](https://www.linkedin.com/in/awale-abdi/)
