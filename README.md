<h1 align="center">🧠 Time Series Forecasting using Deep Learning</h1>

<p align="center">
  <b>Predicting future trends with MLP, CNN, LSTM, and hybrid CNN-LSTM models</b>  
  <br/>
  <a href="https://github.com/Roshan-prakhar/machine-learning-1/stargazers">
    <img src="https://img.shields.io/github/stars/Roshan-prakhar/machine-learning-1?style=social" alt="GitHub Stars">
  </a>
  <a href="https://github.com/Roshan-prakhar/machine-learning-1/network/members">
    <img src="https://img.shields.io/github/forks/Roshan-prakhar/machine-learning-1?style=social" alt="GitHub Forks">
  </a>
  <a href="https://github.com/Roshan-prakhar/machine-learning-1">
    <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License: MIT">
  </a>
</p>

---

## 📘 Overview
This project demonstrates how **deep learning architectures** can be applied to **time series forecasting** tasks.  
It compares multiple models — **MLP, CNN, LSTM, and CNN-LSTM hybrids** — to predict future sales based on historical data trends and seasonality.

---

## 🗂️ Dataset
The models were trained on publicly available Kaggle datasets:

- [Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales)
- [Store Item Demand Forecasting Challenge](https://www.kaggle.com/c/demand-forecasting-kernels-only)

**Data Period:** `2013-01-01 → 2017-12-31`

| Feature | Description |
|----------|--------------|
| `shop_id` | Unique identifier for a shop |
| `item_id` | Unique identifier for a product |
| `item_cnt_day` | Number of items sold per day |
| `item_price` | Current price of the item |
| `date` | Date of sale |
| `date_block_num` | Month index (Jan 2013 = 0) |

---

## ⚙️ Implementation Details

**Languages & Libraries**
```python
Python, NumPy, Pandas, TensorFlow, Scikit-learn, Matplotlib, Seaborn
