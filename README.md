# ECommerce-Churn-Prediction

Customer churn significantly impacts the profitability of ecommerce platforms, making it essential to identify and retain at-risk users. This project leverages machine learning techniques to predict churn and provide actionable insights to improve user retention, satisfaction, and overall platform performance.

# **Problem Statement**
Churn occurs when users disengage with an ecommerce platform, often due to unresolved complaints, poor operational efficiency, or lack of engagement. This project aims to develop accurate and scalable churn prediction models to address these challenges, enabling businesses to proactively reduce churn rates.

# **Methods Used**
1. **Data Preparation**:
   - Cleaning: Missing values removed, features scaled for numerical consistency.
   - Feature Selection: Lasso regression identified key predictors like satisfaction score, complaints, cashback amount, and days since last order.

2. **Models Implemented**:
   - Logistic Regression:
     - Operational model (AUC: 0.837)
     - Transactional model (AUC: 0.724)
   - Random Forest:
     - Behavioral/Transactional model (AUC: 0.874)
     - Operational model (AUC: 0.751)
   - XGBoost:
     - Combined all features for superior performance (AUC: 0.992).

3. **Evaluation**:
   - Metrics: AUC and ROC curves were used to compare model performance and assess predictive power.

 **Results**
- The XGBoost model achieved exceptional accuracy (AUC: 0.992), demonstrating the importance of integrating diverse features for churn prediction.
- Logistic Regression highlighted key churn drivers, such as complaints and tenure, across satisfaction, activity, and transactional models.
- Random Forest models emphasized the significance of user engagement and operational metrics, achieving strong performance in predicting churn.

# **Future Directions**
1. **Targeted Retention Strategies**:
   - Personalize incentives like cashback and coupons for high-risk users.
   - Address operational issues, such as delivery delays and complaint resolution.

2. **Enhanced Models**:
   - Explore neural networks to improve predictive accuracy.
   - Incorporate additional external features for a comprehensive analysis.

3. **Operational Insights**:
   - Reduce churn drivers like inactivity and transactional fatigue through optimized user engagement strategies.
   - Focus on demographic-specific interventions based on city tier, gender, and tenure.

This project highlights the power of predictive analytics in ecommerce, combining advanced machine learning with actionable insights to address churn challenges effectively.
