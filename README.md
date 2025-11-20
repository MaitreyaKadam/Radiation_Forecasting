## Forecasting Solar Radiation and Spurious Correlation Testing of Melbourne PPI 📈

🚀 Overview 
- This project focuses on two comprehensive time series analysis tasks: 1) Forecasting the monthly solar radiation using advanced modeling techniques, and 2) Investigating for the spurious correlation between quaterly Melbourne Residential Property Price Index and Victorian Population Change.

🎯 Primary Objective
- Developing and selecting the best time series regression model to provide the most accurate 2-year forecast for the monthly average solar radiation which is validated using the MASE.
- Applying stationarity tests and correlation analysis to determine the validity of the apparent relationship between the Melbourne PPI and Population Change.

📌 Key Insights
- The Holt-Winters multiplicative method provided the most accurate solar radiation forecast, achieving the lowest MASE score among the models tested
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/856e59f1-5bf8-454a-bc2c-ea87d86b869d" />
  <img width="1126" height="745" alt="image" src="https://github.com/user-attachments/assets/5e7a02ec-d10e-426b-b584-f8282741a6b7" />
- The correlation between Melbourne PPI and Population Change was found to be spurious. Using Prewhitening and stationarity techniques, no significant correlation remained.
<img width="1265" height="788" alt="image" src="https://github.com/user-attachments/assets/e812a68f-40ef-470f-8728-4c7165e408f8" />
<img width="1292" height="807" alt="image" src="https://github.com/user-attachments/assets/f191bd5a-7309-429f-b794-ab877d7be238" />

Tech Stack Used 🧰
- R for data cleaning, analysis and visualisation
- forecast package for time series forecasting and decomposition techniques.
- tseries package for stationarity testing using ADF and related diagnostics
- dynlm package for contructing and evaluating distributed lag models.
