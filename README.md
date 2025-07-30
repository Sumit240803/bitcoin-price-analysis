

# 📈 Bitcoin Price Prediction using Machine Learning

Predicting the future price of Bitcoin using historical data and machine learning techniques like Linear Regression, Support Vector Regression (SVR), and Long Short-Term Memory (LSTM) neural networks.

---

## 🚀 Features

* End-to-end data pipeline for time series forecasting
* Multiple ML models: Linear Regression, SVR, and LSTM
* Feature engineering with moving averages and lag variables
* Model performance evaluation using MAE, RMSE, and R²
* Visualizations for insights and model predictions

---

## 🛠️ Tech Stack

* **Languages**: Python
* **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, TensorFlow/Keras
* **Data Source**: Yahoo Finance (via `yfinance`)

---

## 🧠 Models Used

| Model               | Description                              |
| ------------------- | ---------------------------------------- |
| Linear Regression   | Basic regression to model linear trends  |
| SVR (RBF Kernel)    | Captures non-linear trends in pricing    |
| LSTM Neural Network | Deep learning model for time series data |

---


## 📈 Results

| Model     | MAE    | RMSE   | R² Score |
| --------- | ------ | ------ | -------- |
| Linear    | 570.23 | 812.15 | 0.78     |
| SVR (RBF) | 462.74 | 675.20 | 0.85     |
| LSTM      | 390.52 | 602.37 | 0.89     |

> ✅ LSTM outperformed traditional models in capturing complex time-dependent patterns.

---

## ⚙️ How to Run

```bash
# Clone the repository
git clone https://github.com/Sumit240803/bitcoin-price-analysis.git
cd bitcoin-price-prediction

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook notebooks/Bitcoin_Prediction.ipynb
```

---

## 📚 References

* [GeeksforGeeks Tutorial](https://www.geeksforgeeks.org/machine-learning/bitcoin-price-prediction-using-machine-learning-in-python/)
* [Yahoo Finance](https://finance.yahoo.com/)
* [Keras Documentation](https://keras.io/)

---

## 📬 Contact

For questions or collaborations:
**Sumit Goyal** – [LinkedIn](https://www.linkedin.com/in/sumit-goyal-87207a213/) • [Email](mailto:goyalsumit651@gmail.com)

