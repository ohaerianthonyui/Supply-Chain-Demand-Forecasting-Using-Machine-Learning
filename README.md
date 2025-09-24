# Supply-Chain-Demand-Forecasting-Using-Machine-Learning



# **Project: Supply Chain Demand Forecasting Using Machine Learning**

## **Introduction**

Accurate demand forecasting is critical for supply chain optimization, helping businesses reduce inventory costs, avoid stockouts, and improve customer satisfaction. This project leverages historical retail sales data to build predictive models that forecast product demand at the store level. Using advanced machine learning techniques like XGBoost and CatBoost, the goal is to generate accurate sales predictions that can inform inventory management decisions.

---

## **Objective**

* Develop a robust demand forecasting model to predict daily sales for various products across stores.
* Engineer relevant time series and promotional features from transactional data.
* Use machine learning models (XGBoost and CatBoost) to capture complex patterns in sales data.
* Blend predictions from both models to improve accuracy.
* Evaluate model performance using key metrics like RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error).
* Deliver actionable insights for supply chain optimization.

---

## **Findings**

* Data preprocessing included merging transaction, product, and coupon datasets, and creating time-related features (day of week, month, year).
* Lag features (sales from previous days) and rolling statistics (mean, std over past windows) were crucial to capture temporal dependencies.
* Both XGBoost and CatBoost models were trained and validated using early stopping to avoid overfitting.
* Model tuning (hyperparameter optimization) improved prediction accuracy substantially.
* A blended model, averaging XGBoost and CatBoost predictions, achieved the best validation RMSE of approximately 1066.7 and MAE of 757.5, outperforming individual models.
* Feature importance analysis highlighted that recent sales lag features and promotional campaign indicators significantly influenced demand.

---

## **Conclusion**

The project demonstrates how combining gradient boosting models with thoughtful feature engineering can effectively forecast product demand in retail. The blended model’s accuracy indicates its potential value for supply chain managers to optimize inventory, reduce costs, and improve service levels. Future work could extend to integrating external factors like holidays or weather data, and deploying the model as a real-time forecasting tool.

---
