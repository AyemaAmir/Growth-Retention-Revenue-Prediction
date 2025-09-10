# 📊 New Users Prediction & Retention Forecasting

### 📌 Project Overview
This project applies time-series forecasting and business analytics to predict new user growth, estimate retention, and calculate potential revenue contribution. The model is validated with historical data and presented in an interactive Power BI dashboard for actionable insights.

### ⚙️ Features

#### 🔮 Forecasting & Predictions
- **Predicts** new user acquisitions for the upcoming month.
- **Estimates** user retention at different intervals (Day 1, Day 7, Day 30).
- **Calculates** expected revenue contribution from retained users over a 120-day lifecycle.

#### 📊 Dashboard Insights
The Power BI dashboard provides:
- **Summary KPIs** – Forecasted new users, retained users, and expected revenue.
- **Retention Selector** – Choose retention day (1, 7, 30) to see corresponding retention rates.
- **Trend Graphs** – Daily acquisition forecasts vs. actual data for validation.
- **Drill-down Navigation** – Compare New vs Active Users and view detailed Retention Rates.
<img width="892" height="500" alt="image" src="https://github.com/user-attachments/assets/3bb3d25c-fb33-4553-a13b-139b977ed255" />
<img width="898" height="491" alt="image" src="https://github.com/user-attachments/assets/bec0cba7-3230-48e9-ba72-23ba3de97556" />
<img width="893" height="498" alt="image" src="https://github.com/user-attachments/assets/f1c644be-2567-408c-aa09-9585d766ef42" />

### 🛠️ Tech Stack
Python → Data preprocessing, Prophet forecasting model
Prophet → Time-series forecasting with daily, weekly seasonality
Power BI → Dashboarding & visualization
SQL → Data extraction & validation
Pandas, NumPy, Matplotlib → Data wrangling and analysis

### 🔍 Methodology

#### Data Understanding & Collection
- Collected dummy user acquisition and retention data.
- Aligned business terms with dataset features for consistency.

#### Forecasting with Prophet
- Chosen for its ability to capture daily, weekly, and monthly seasonality.
- Data split monthly for training and validation.
- Verified accuracy by back-testing predictions on a past month → achieved ~90% accuracy.

#### Retention & Revenue Modeling
- Applied formulas to estimate:
    - Retention rates
    - Number of retained users
    - Revenue contribution within the first 120 days

#### Dashboard Development
- Integrated forecasts and business metrics into an interactive Power BI dashboard.

### 📈 Example Insight
“We expect ~10,000 new users next month, of which ~7,000 are likely to be retained, generating an estimated ~7M in revenue during their first 120 days.”
*(Note: Numbers are illustrative examples using dummy data.)*

### 🚀 Future Enhancements
- Automate pipeline for real-time data refresh.
- Add churn probability models for deeper retention analysis.
- Expand dashboard with cohort analysis and campaign ROI tracking.

---

### ✅ Conclusion
This project demonstrates how forecasting + visualization can bridge data science and business decision-m
