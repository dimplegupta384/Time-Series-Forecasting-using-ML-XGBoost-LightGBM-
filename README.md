# Time-Series Forecasting with XGBoost

## Business Background and Objectives
- Importance of demand forecasting in retail (esp. grocery)
- Objective: Forecast sales for Corporación Favorita
- Impact: Better inventory planning and sales optimization
  
- ## Data Source and Understanding
- Source: Kaggle Competition (with hyperlink)
- Store data: store_nbr, family, sales, onpromotion, cluster
- Holiday data: type, locale
- Macro indicators: oil prices
  
## Framework and Method
- Data cleaning and preprocessing
- Feature engineering (categorical → numerical)
- Time-based features (day, quarter, etc.)
- Model training using XGBoost
- Evaluation (Normalized RMSE)

  ## Results and Insights
- Model performance (RMSE = 0.005)
- Out-of-sample predictions
- Visualization findings:
  - Sales peak on Sundays
  - Q2 has the highest sales
    
## Credit
Dataset Source: [store sales series forecasting dataset](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data)





