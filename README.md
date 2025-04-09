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

## 📊 Business Insights
- XGBoost outperformed other models in accuracy and generalization.
- External factors like holidays and oil prices had a noticeable influence on sales patterns.
- Suggest improved inventory planning and store-level promotions based on weekly demand spikes.

---

## 🔗 Credits
Created by Saravanan Palanisamy 

