Principal Investigator: Nathan Armani
Created: May 12, 2025

🧠 Overview
This R script performs time series analysis and forecasting of salary data using three models:
* Linear
* Quadratic
* Exponential

It evaluates model performance using R², AIC, and BIC, and outputs comparison tables, visualizations, and forecasted values based on user-specified parameters.

📂 Repository Contents
TimeSeriesAnalysis.R – Main R script

Book1.xlsx 

README.md – This file

⚙️ Features
✅ Fits and compares 3 time series models
✅ Automatically selects and recommends the best model
✅ Optionally performs forecasting for user-defined years
✅ Interactive plotting: separate or combined models
✅ Outputs model coefficients, diagnostics, and plots

🛠️ Requirements
Ensure the following R packages are installed:
install.packages(c("readxl", "ggplot2", "tidyr", "dplyr"))

🚀 Getting Started
1. Edit your data: Ensure the Excel sheet has columns Year and Salary (Millions).
2. Open TimeSeriesAnalysis.R in RStudio or R GUI.
3. Run the script and follow prompts:
3.1. Plot format: yes for individual model plots, no for combined
3.2. Forecasting: yes or no and define forecast range if enabled
4. Review Outputs:
4.1. Coefficient tables
4.2. AIC/BIC results
4.3. Forecast tables (if enabled)
4.4. Recommended model summary
4.5. Data visualizations

🧪 Sample Output
MODEL SELECTION SUMMARY:
       Metric         Model
    Lowest AIC     Quadratic
    Lowest BIC     Quadratic
   Highest R²     Exponential
✅ Recommended Model: **Quadratic** (based on combined AIC, BIC, and R² criteria)

📊 Visuals
* Combined Model Comparison Plot
* Individual Model Forecasting Plots
* Forecast Plots for Future Years

📌 Notes
* Script clears the R environment and console at runtime.
* Requires user interaction via readline() for options.
* Forecasting is optional and only executed when selected.
* Visual output uses ggplot2 with publication-ready styling.

📝 License
This project is licensed under the MIT License.
Feel free to reuse, adapt, or build upon it with credit.
