


📈 Microsoft Stock Price Prediction

A machine learning project that predicts Microsoft (MSFT) stock closing prices using multiple models including:

Linear Regression

Random Forest Regressor

XGBoost

LSTM (Deep Learning)

The project includes full data preprocessing, feature engineering, model training, evaluation, and visualization.

📂 Project Structure
Microsoft-Stock-Prediction/
│
├── MicrosoftStock.csv        # Dataset
├── stock_prediction.ipynb    # Jupyter Notebook
├── README.md                 # Project documentation
└── requirements.txt          # (optional) Required packages

🧠 Models Used
🔹 1. Linear Regression

Baseline model to understand trends and linear behavior.

🔹 2. Random Forest Regressor

Captures non-linear relationships and performs well on tabular financial data.

🔹 3. XGBoost Regressor

Boosted tree model optimized for high accuracy.

🔹 4. LSTM (Long Short-Term Memory Network)

Deep learning model for time-series forecasting.

🧹 Data Preprocessing

Loaded Microsoft stock data

Converted date column

Scaled numerical features using MinMaxScaler

Created time-series sequences (lookback) for LSTM

Train-test split

📊 Model Evaluation Metrics

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

Inverse scaling applied before evaluation for real price predictions.
