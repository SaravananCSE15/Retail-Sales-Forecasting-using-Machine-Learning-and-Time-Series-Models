# 🛍️ Retail Sales Forecasting using Machine Learning and Time Series Models

## 📌 Objective
To forecast weekly sales for different retail store-product combinations using models like ARIMA, XGBoost, Random Forest, Prophet, and more.

## 📁 Project Structure
- `notebooks/Saravanan_P_Assignment.ipynb`: Complete modeling and evaluation code.
- `outputs/submission_saravanan__P.csv`: Final predictions for the test dataset.
- `outputs/Final_Model_Comparison.pdf`: Summary of model results and business insights.

## ⚙️ How to Run
1. Clone or download this repository.
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the notebook:
    ```bash
    jupyter notebook notebooks/Final_Sales_Forecasting.ipynb
    ```
4. Run all cells to reproduce results and generate predictions.

## 📈 Best Model: XGBoost
- RMSE: 255.10
- R²: 0.9465
- MAPE: 0.7773%
- 
## 🔍 Visual Comparison
- All models were evaluated by plotting actual vs. predicted sales.
- XGBoost produced the most consistent trend matching real sales across various categories.
- ARIMA and Prophet showed seasonality but lacked in predictive strength for irregular patterns.
- Naïve baseline failed on dynamic patterns.

## 📌 Business Insights
1. Model Selection for Deployment
- Use XGBoost for forecasting as it balances speed, accuracy, and interpretability.
- Avoid using ARIMA/Prophet for short-term planning due to volatility.

2. Holiday & Promotion Sensitivity
- Sales spiked during national holidays and special events.
- Black Friday, Ecuadorian holidays, and Christmas contributed to large sales jumps.
- Promotions provided short-term boosts—can be leveraged for clearance or upselling.

3. Oil Price Impact
- Affected overall cost-sensitive categories indirectly (transportation-heavy).

## 📈 Recommendations
- 🏪 Inventory Planning: Use forecasts to pre-stock for holidays and weekends.
- 🎯 Targeted Promotions: Run location-based promotions during off-peak weeks.
- 📉 Avoid Overfitting: Monitor model performance regularly and retrain quarterly.
- 🔄 Retrain: Incorporate recent holiday or pricing changes to stay relevant.

## ✅ Conclusion
- The XGBoost model is production-ready with strong accuracy and business relevance.
- It can significantly aid retail planning, logistics, and marketing strategies.

## 🔗 Credits
Created by Saravanan Palanisamy 

