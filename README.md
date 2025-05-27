🛍️ Retail Sales Forecasting with Prophet + Hybrid Model
📌 Project Overview
This project demonstrates a robust time series forecasting pipeline applied to retail sales data using:

📈 Facebook Prophet for capturing seasonality and trends

🧠 A Hybrid LSTM + Prophet model for performance enhancement

📉 Evaluation via Mean Absolute Error (MAE)

📊 Visual insights into trends, seasonality, and model predictions

🔗 Author: Tony Ochieng

🔍 Objective
To forecast weekly sales for retail stores with high accuracy by:

Leveraging Prophet's interpretability for seasonality/trend decomposition.

Using LSTM to capture residual patterns not modeled by Prophet.

Combining both outputs in a hybrid framework.

📂 Notebook Contents
Data Preprocessing

Aggregated sales data weekly

Handled missing values

Forecasting with Prophet

Trend + yearly seasonality components visualized

Forecast generated for Store 1

Hybrid Modeling

Residuals from Prophet modeled using LSTM

Final prediction = Prophet Forecast + LSTM Residual Forecast

📉 Model Performance
Prophet MAE (last 12 weeks): 7,650.35

Hybrid Forecasting MAE (last 12 weeks): 3,354.83 ✅

📸 Visual Insights
✅ Hybrid Forecast vs Actual Sales – Store 1
<img src="Hybrid%20Forecast%20vs%20Actual%20Sales%20(Store%201%20%20).png" width="100%">
Clearly shows the Hybrid model’s enhanced alignment with actual sales trends.

🔍 Forecast Components (Trend + Seasonality)
<img src="Forecast%20components(trend,seasonality).png" width="100%">
Prophet decomposed the sales time series to reveal underlying long-term trends and seasonal effects.

🧠 Skills Demonstrated
Time series forecasting

Model ensembling (Prophet + LSTM)

Data preprocessing & visualization

Error analysis (MAE)

Model interpretability

📎 Usage
bash
Copy
Edit
# Clone the repo
git clone https://github.com/yourusername/Retail_Sales_Forecasting.git

# Run the notebook in Jupyter or Colab
🤝 Let's Connect!
If this project aligns with your goals or interests, feel free to connect or collaborate:

📇 Tony Ochieng on LinkedIn


