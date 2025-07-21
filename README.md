# 📈 MRF Stock Price Prediction using Linear Regression (NSE: MRF.NS)

A beginner-friendly machine learning project in Python that predicts the **next day's closing price** of **MRF stock** using supervised learning.

This project uses **Linear Regression**, basic feature engineering, data visualization, and real-world stock data from **Yahoo Finance**.

---

## 🧾 Project Summary

- **Goal:** Predict MRF's next-day stock closing price using the previous day’s price.
- **Model:** Linear Regression
- **Data Source:** Yahoo Finance (2015–2025)
- **Libraries Used:** `yfinance`, `pandas`, `scikit-learn`, `matplotlib`, `numpy`

---

## 📁 Project Structure

```
📦 stock_prediction
├── mrf_stock_ml.py         # Main Python code
├── README.md               # This file
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```
git clone https://github.com/Karanpr-18/Stock-prediction
cd stock_prediction
```

### 2. Install Dependencies

Use `pip` to install required libraries:

```
pip install yfinance pandas scikit-learn matplotlib numpy
```

### 3. Run the Script

```
python mrf_stock_ml.py
```

---

## 🛠️ What the Script Does

### ✅ Step-by-Step Flow:

1. **Download stock data** from [Yahoo Finance](https://finance.yahoo.com/) using `yfinance`.
2. **Create a lag feature** using the previous day's closing price (`Prev_Close`).
3. **Train-test split** using chronological order (no shuffling).
4. **Train a Linear Regression model** on the training data.
5. **Evaluate** using Root Mean Squared Error (**RMSE**) and R² Score (**Accuracy %**).
6. **Visualize** actual vs. predicted prices using `matplotlib`.

---

## 📊 Example Output

```
RMSE: 1,572.19 ₹
Model Accuracy % : 99.48%
```

📈 The script also shows a line chart comparing actual vs. predicted prices.

---
<img width="1665" height="547" alt="image" src="https://github.com/user-attachments/assets/bdef2dee-f985-493d-bffb-13b77ac5a0f3" />


## 📌 What You’ll Learn

- How to use `yfinance` to collect stock data
- Lag-based feature engineering
- Train-test splitting for time-series problems
- Training and evaluating a regression model
- Plotting predictions using real-time stock data

---

## 📦 Dependencies

```
yfinance
pandas
scikit-learn
matplotlib
numpy
```

Or install manually as shown earlier.

---

## ⚠️ Disclaimer

> This project is for **educational purposes only** and should **not** be used for real-world trading or financial decisions. Stock markets are unpredictable and affected by many external factors beyond this model's scope.

---

## 👨‍💻 Author

**Karanpr-18**  
[GitHub](https://github.com/Karanpr-18)
---

## 📝 License

This project is under the [MIT License](LICENSE).
```
