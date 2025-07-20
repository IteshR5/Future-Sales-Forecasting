# 📈 Sales Forecasting Using Time Series Models

This project implements time series forecasting using classical statistical models to predict future product sales for individual stores. The goal is to empower businesses to make data-driven inventory and supply chain decisions by anticipating demand patterns over time.

---

## 🧠 Problem Description

Retailers face challenges in predicting product demand accurately due to seasonal trends, promotions, or external events. Traditional heuristics-based methods often lead to:

- ❌ Overstocking or understocking inventory
- ❌ Missed revenue opportunities due to poor planning
- ❌ Inefficient use of marketing and logistics resources

---

## 💡 Solution Provided

This notebook leverages **ARIMA** and **SARIMAX** models to forecast sales for a specific store-item combination over time. Key techniques used:

- ✅ Time series decomposition for seasonality and trend analysis
- ✅ Stationarity checks using ADF test
- ✅ Autocorrelation and Partial Autocorrelation (ACF, PACF) analysis
- ✅ ARIMA & SARIMAX model implementation
- ✅ Model evaluation using RMSE

---

## 🏭 Industry Impact

Time series forecasting is widely used in:

- 🛒 **Retail**: Stock prediction at SKU-level per store
- 🏬 **Inventory Management**: Minimizing carrying and shortage costs
- 🚚 **Supply Chain**: Demand planning and order management
- 📊 **Finance**: Revenue forecasting and risk management

Implementing models like SARIMAX helps companies plan inventory and operations more effectively, leading to reduced waste and improved profitability.

---

## ✨ Key Features

- 📅 Converts date column to datetime index
- 🔍 Filters data by `store_id` and `item_id` for targeted forecasting
- 📈 Performs trend/seasonality decomposition
- 📉 Implements ADF Test for stationarity
- 🔄 Uses ARIMA & SARIMAX models with hyperparameter tuning
- 🧪 Evaluates models with Root Mean Squared Error (RMSE)

---

## 🔧 Tools & Libraries Used

- `pandas` – Data manipulation
- `numpy` – Numerical operations
- `matplotlib`, `seaborn` – Visualization
- `statsmodels` – Time series modeling (ARIMA, SARIMAX, ADF test, decomposition)
- `scikit-learn` – Model evaluation metrics
- `warnings`, `time` – Execution and performance handling

---

## Contributing
Contributions are welcome! To contribute:

1. Fork the repository.

2. Create a new branch:
   
  ```
  git checkout -b feature/your-feature-name
  ```

3. Make your changes and commit them:

  ```
  git commit -m 'Add your feature description'
  ```

4. Push to the branch:
  
  ```
  git push origin feature/your-feature-name
  ```

5. Open a pull request with a description of your changes.
   
**Thank you for choosing this project. Hoping that this project proves useful and delivers a seamless experience for your needs!**
