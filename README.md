
## 📈 Stock Price Prediction using Time Series

A time series forecasting project that predicts stock prices using historical data and models such as ARIMA, ETS, and Prophet. The goal is to analyze patterns, detect seasonality and trends, and forecast future prices to support investment decision-making.

---

### 📂 Project Structure

```
├── data/                      # Raw & cleaned data
├── notebooks/                # Jupyter notebooks for EDA & modeling
├── models/                   # Saved model files
├── plots/                    # Visualizations of trends & predictions
├── stock_forecasting.py      # Script to train and evaluate models
├── requirements.txt          # Project dependencies
└── README.md                 # Project documentation
```

---

### 🔧 Technologies Used

* **Python 3.10**
* **Pandas**, **NumPy**
* **Matplotlib**, **Seaborn**
* **Scikit-learn**
* **Statsmodels** (ARIMA, ETS)
* **Prophet (optional)**

---

### 📊 Problem Statement

To forecast future stock prices based on past performance by applying time series models and evaluating them with appropriate metrics.

---

### ✅ Features

* EDA with trend, seasonality, and correlation analysis
* Data cleaning and handling missing values
* Implemented models: ARIMA, ETS, Prophet (optional)
* Model evaluation with RMSE, MAPE
* Visualized historical vs predicted prices
* Comparative analysis of models

---

### 📁 Dataset

* Source: [Yahoo Finance](https://finance.yahoo.com) or \[Kaggle datasets]
* Features: Date, Open, High, Low, Close, Volume

---

### 📉 Results

| Model   | RMSE | MAPE (%) |
| ------- | ---- | -------- |
| ARIMA   | 12.5 | 4.2      |
| ETS     | 13.2 | 4.7      |
| Prophet | 11.8 | 3.9      |

*Results may vary depending on stock ticker and data range.*

---

### 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
   cd stock-price-prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or Python script:

   ```bash
   jupyter notebook notebooks/stock_forecasting.ipynb
   ```

---

### 🧠 Future Improvements

* Add LSTM/RNN deep learning models
* Use real-time stock data via APIs
* Integrate with a frontend dashboard using Streamlit

---

### 📩 Contact

**Mukund Mane**
📧 [manemukund8112@gmail.com](mailto:manemukund8112@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/mukund-mane-43604220b/)


