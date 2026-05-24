# Chicago Airbnb Demand Forecasting

## Project Overview
This project focuses on forecasting monthly Airbnb demand in Chicago using time series forecasting techniques in R. Historical Airbnb review data was analyzed to identify trends, seasonality, and recurring demand patterns. Multiple forecasting models were developed and compared to determine the most accurate forecasting approach.

The project demonstrates practical applications of statistical forecasting, machine learning, exploratory data analysis, and business analytics.

---

## Objectives
- Analyze Airbnb demand trends and seasonal behavior
- Compare multiple forecasting models
- Evaluate forecasting accuracy using statistical metrics
- Generate future Airbnb demand forecasts
- Support data-driven decision making in the hospitality industry

---

## Technologies Used
- R Programming
- fpp3 Package
- ARIMA
- ETS
- STL Decomposition
- Neural Networks (NNETAR)
- Time Series Forecasting
- Data Visualization

---

## Dataset
The project uses Airbnb review data as a proxy for customer demand. The data was aggregated into monthly counts to create a time series dataset suitable for forecasting analysis.

Data preparation steps included:
- Monthly aggregation
- Time indexing
- Log transformation
- Train-test split

---

## Forecasting Models
### Baseline Models
- Mean
- Naïve
- Seasonal Naïve
- Drift

### Advanced Models
- ETS
- ARIMA
- STL + ETS
- Neural Network (NNETAR)
- Combination Forecasting Model

---

## Model Evaluation
Models were evaluated using:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- MAPE (Mean Absolute Percentage Error)

### Best Performing Model
The ARIMA model achieved the highest forecasting accuracy with:
- RMSE: 0.0386
- MAE: 0.0279
- MAPE: 0.304

---

## Key Findings
- Airbnb demand shows strong seasonal patterns
- ARIMA outperformed all other forecasting models
- STL + ETS produced competitive results
- Neural network models were less effective for this dataset
- More complex models did not necessarily improve forecasting accuracy

---

## Final Forecast
The final ARIMA model was re-fitted using the complete dataset and used to generate a 12-month forecast for future Airbnb demand in Chicago.

The results indicate:
- Stable seasonal demand patterns
- Predictable fluctuations in demand
- Useful insights for pricing and resource planning

---

## Files Included
- `Final_Project.Rmd` → R Markdown source code
- `Final_Report_Amit.pdf` → Final project report
- `Final_project.pptx` → Project presentation

---

## Learning Outcomes
Through this project, I gained hands-on experience in:
- Time Series Analysis
- Statistical Forecasting
- R Programming
- Data Visualization
- Forecast Accuracy Evaluation
- Business Analytics
- Model Comparison Techniques

---

## Author
**Amit Chaulagain**  
MS in Data Analytics – Oklahoma City University  
Aspiring Data Analyst | SQL | Power BI | Python | R
