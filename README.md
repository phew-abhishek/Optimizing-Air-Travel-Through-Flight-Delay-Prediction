# Optimizing Air Travel: Data-Driven Analysis ✈️

## Overview
This project applies **data analytics and machine learning** to identify, predict, and mitigate flight delays for a smoother travel experience.  
By analyzing **historical flight data**, we uncover delay patterns, predict delay risks, estimate delay durations, and introduce an **Operational Adjustability Index (OAI)** to focus on delays airlines can control.

## Objectives
1. **Understand Delay Patterns** – Analyze trends, seasonal effects, and major delay contributors.  
2. **Predict Delay Risk** – Classification model to determine if a flight will be delayed.  
3. **Estimate Delay Duration** – Regression model to forecast delay length in minutes.  
4. **Focus on Controllable Delays** – OAI prioritizes delays under airline control.

## Methodology
- **EDA:** Identify delay causes, seasonal variations, and carrier-specific patterns.  
- **Modeling:**  
  - Classification → **Random Forest Classifier** (97.6% accuracy, AUC = 0.9978)  
  - Regression → **Random Forest Regressor** (Best MAE, RMSE, R² among tested models)  
- **SHAP Analysis:** Feature importance weighted by controllability.  
- **OAI Metric:** Quantifies controllability (Avg. OAI = 0.85; 89% flights in high controllability zone).

## Key Insights
- **Top Delay Drivers:** Late aircraft & carrier delays dominate.  
- **Seasonal Trends:** Summer = highest delays; Fall = lowest.  
- **Impact:** 50% reduction in controllable delays could save ~251M minutes/year (~$25.18B).  
- **Bottlenecks:** Peak-time congestion at hubs (LAX, O’Hare) and specific airline-route combos.

## Recommendations
- Target controllable delays through operational improvements.  
- Address peak-hour congestion at major hubs.  
- Prepare for high-impact uncontrollable events (e.g., severe weather).


## Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Scikit-learn** (Random Forest, Gradient Boosting, Linear Models)  
- **SHAP** (Model interpretability)  
- **Jupyter Notebook** for analysis & visualization  

## Author
**Abhishek Soni**  
4th Year, Metallurgical & Materials Engineering  
IIT Roorkee


