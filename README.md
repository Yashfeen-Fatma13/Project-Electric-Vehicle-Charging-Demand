Project Summary: EV Charging Demand Forecasting:


This project aims to forecast electric vehicle (EV) charging demand by leveraging historical energy usage data, weather data, and time-series forecasting models. The final goal was to derive actionable insights through visualizations for better energy planning, load management, and charging infrastructure optimization.


Step-by-Step Process:

1. Data Collection

You gathered two main datasets:

EV Charging Data: Containing datetime, energy consumption (kWh), and station-level details.

Weather Data: Including humidity, temperature, and wind speed corresponding to each time entry.

Additionally, forecast output from Facebook Prophet was generated to predict future energy demand.

2. Data Merging & Preprocessing

The datasets were merged using a common datetime key.

Ensured datetime formatting was consistent to avoid mismatches.

Cleaned and formatted data in Microsoft Excel, removing blanks, fixing column types, and organizing structure.

3. Forecasting with Prophet

Applied the Prophet model in Python to perform time-series forecasting of energy demand.

Generated the following metrics:

yhat: Predicted energy demand.

yhat_lower & yhat_upper: Confidence intervals.


These predictions were aligned with actual data for comparative analysis.

4. Feature Impact Analysis

Used Random Forest Regressor to analyze how weather variables (temperature, humidity, wind speed) impact EV energy consumption.

Identified that temperature and humidity had significant influence on energy usage patterns.

5. Visualization & Dashboard Creation

Created powerful visual dashboards using Tableau (and earlier, Power BI):

Line Chart: Compared actual vs. predicted energy usage (Energy_kWh vs. yhat).

Heatmaps: Visualized hourly and daily energy consumption patterns.

Scatter Plots: Demonstrated how temperature and humidity influenced energy demand.

Ensured dashboards followed a clean, readable layout with corrected labels and intuitive design.

6. Report & Documentation

Prepared a professional project report covering Introduction, Abstract, Tools Used, Project Steps, and Conclusion.

Drafted a Charging Optimization Strategy outlining how forecast insights can improve real-world EV charging efficiency.

7. Final Deliverables

A merged Excel dataset ready for future analysis.

A fully designed Tableau dashboard visualizing demand trends and forecasts.

A polished PDF report summarizing the project for presentation or resume use.

A strategic plan to optimize charging schedules, energy resource allocation, and infrastructure planning.
