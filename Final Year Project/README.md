# Effect of Anthropogenic Factors on Temparature Variation in Malaysia

## Project Overview
This project analyzes the effects of human-induced factors, including Gross Domestic Product (GDP), population density, and electricity consumption, on temperature variations in Malaysia. Using statistical and machine learning models, such as Multiple Linear Regression (MLR) and Support Vector Regression (SVR), the study explores the significance of these factors in driving temperature changes.

## Key Findings
MLR Model: Achieved an approximately 82.8% predictive performance.
SVR Model: Outperformed MLR with 95.26% predictive accuracy, showcasing lower error values (RMSE = 0.3030, MAE = 0.0634).
The SVR model is deemed the most suitable for predicting temperature variations.

## Project Goals
- Analyze the impact of human-induced factors on temperature in Malaysia.
- Compare the effectiveness of MLR and SVR models in predicting temperature changes.
- Provide actionable insights for policymakers on managing the environmental impact of economic growth and urbanization.

## Technologies Used

- Python (for data analysis and modeling)
- SPSS (for statistical analysis)

## Libraries:
- Pandas, NumPy, Matplotlib, Scikit-learn for data preprocessing and machine learning models

## Data Sources

Temperature Data: https://mymetdata.met.gov.my/my-order/eyJpdiI6ImY0VE1OUFdiTjlEb3dCUjIyTTY1RUE9PSIsInZhbHVlIjoiQVplaVd6VnNoT09oZG0rMHB3ZmI0UT09IiwibWFjIjoiM2Y4NTJiM2VlNDJjODJjM2QxNmYwZDIwOWUxYzRlOGQ0MzA3OWQwMzM4YzM0MWU5NzkyMzhiNTNjMjQzOWE3ZCIsInRhZyI6IiJ9
GDP : https://open.dosm.gov.my/data-catalogue/gdp_gni_annual_real?series=growth-yoy&visual=gdp
Population Density : https://www.macrotrends.net/global-metrics/countries/MYS/malaysia/population
Electricity : https://ourworldindata.org/energy/country/malaysia?country=~MYS#per-capita-what-is-the-average-energy-consumption-per-person
