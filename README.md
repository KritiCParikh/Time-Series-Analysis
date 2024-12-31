# Time Series Analysis: Retail & Racing 🏪🏎️ 
A comprehensive analysis of seasonal and non-seasonal time series data using Walmart Sales data and Formula 1 World Championship.

---

## Overview  
This project implements time series analysis and forecasting techniques on two distinct datasets:  
- **Walmart Weekly Sales** (Seasonal)
- **Formula 1 World Championship Results** (Non-Seasonal)
  
---

## Methodology  
The analysis follows the **Box-Jenkins methodology** for both datasets:  

### **1. Data Preprocessing**  
- Handling missing values and outliers  
- Feature engineering  
- Stationarity testing  

### **2. Model Development**  
- ARIMA/SARIMA modeling  
- Parameter estimation  
- Diagnostic checking  
- Model validation  

### **3. Forecasting**  
- Future predictions  
- Confidence intervals  
- Performance metrics  

---

## Project Summaries

## Walmart Weekly Sales Prediction (Seasonal)
**Objective:** Forecast store sales to optimize inventory management and strategic planning.  
**Dataset:** Sales data from 45 Walmart stores (2010-2012) including:  
- **Store Information:** 3 types (A, B, C)  
- **Weekly Sales Data:** By department  
- **External Factors:** Temperature, fuel prices, CPI, unemployment  
- **Holiday Indicators**

**Results:**  
- **Auto-SARIMA** outperformed **Auto-ARIMA** with:  
  - RMSE: 574.43 vs 1,024.50  
  - WMAE: 374.39 vs 594.474

---

## Formula 1 Championship Prediction (Non-Seasonal)
**Objective:** Predict World Champion points based on historical performance.  
**Dataset:** 75 years of F1 data (1950-2024) covering:  
- 1,144 races  
- 859 drivers  
- 212 teams  

**Results:**  
- **ARMA model** performed best with:  
  - RMSE: 90.78 (compared to ARIMA: 172.47 and SARIMA: 280.61)
 
---
# Fascinating Discoveries

## Altitude Impact on F1 Performance

| Team      | Performance Characteristic          |
|-----------|-------------------------------------|
| Mercedes  | Excels at high altitudes           |
| Ferrari   | Dominates at sea level             |
| Red Bull  | Shows consistent adaptability      |

## Walmart Store Performance

| Store Type | Holiday Performance                      |
|------------|------------------------------------------|
| Type A     | Highest average sales during holidays    |
| Type B     | Moderate seasonal fluctuations           |
| Type C     | Most consistent year-round               |

---

## Key Conclusions
1. **Walmart Sales Prediction:**  
   - Strong seasonal patterns, particularly during holidays like Thanksgiving and Christmas.  

2. **Formula 1 Prediction:**  
   - Historical performance is a reliable predictor of future outcomes.  
   - Simpler ARMA models outperform more complex seasonal alternatives.  

**Takeaway:**  
These projects demonstrate how data-driven techniques enable organizations to make informed decisions and optimize performance across diverse business contexts.


---
## Acknowledgments

Thank You to **Vedanth Sirimalla** (@VedSirimalla) for the innovative project ideation and collaboration. His insights were instrumental in:
- Conceptualizing the dual-domain analysis approach  
- Developing the seasonal vs. non-seasonal comparison methodology  
- Implementing advanced time series techniques  

---

References: Kaggle

Thank You. Let’s keep learning and growing together!
