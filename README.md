Financial Anomaly Detection

This project detects financial anomalies in AAPL, VOO, and DIA using LSTM and XGBoost on 20 years of daily stock data. Anomalies are defined as Z-Score > |2| from the 10-day moving average.

XGBoost performed well (DIA: precision 0.92, recall 1.00, F1 0.96), while LSTM struggled due to class imbalance. The results highlight that tree-based models with engineered features are effective for rare-event detection and risk management.

Data was collected via Yahoo Finance API and models implemented in Python using Scikit-learn, TensorFlow, and XGBoost. Visualizations were created with Matplotlib and Plotly. Future work could explore hybrid or attention-based deep learning models.
