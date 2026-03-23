# Project title-
Predictive-Modeling-for-Range-and-Efficiency-in-Electric-Vehicle

Problem Statement- Accurately predicting the driving range and efficiency of electric vehicles (EVs) is a crucial challenge in the automotive industry. Range anxiety remains one of the biggest concerns for EV adoption, and understanding efficiency helps in optimizing powertrain design, charging infrastructure, and consumer confidence.
This project uses Python and machine learning to build a predictive model for range and efficiency of electric vehicles (EVs) based on specifications such as battery capacity, powertrain, and vehicle type.  
EV Range (km) → based on performance and powertrain features.
EV Efficiency (kWh/100km) → based on energy usage patterns.

Methods / Algorithms-

Data Preprocessing: Handling missing values, feature scaling, and transformations.
Exploratory Data Analysis (EDA): Identifying correlations between vehicle specs and range/efficiency.
Machine Learning Models:
Regression models for predicting range
Regression models for predicting efficiency
Evaluation Metrics: Mean Squared Error (MSE) and R-squared (R²).

 Model                  | Target       | MSE      | R²      |
|------------------------|-------------|----------|---------|
| Regression Models      | Range       | 3675.65  | 0.7233  |
| Regression Models      | Efficiency  | 338.70   | 0.7032  |
 
The models perform well in predicting EV range and efficiency, capturing over 70% of the variance in both cases. This demonstrates that the features chosen — like battery capacity, powertrain, and vehicle type are effective for estimating real-world EV performance. These results provide a strong foundation for further model improvements and practical applications.
