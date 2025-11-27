🧠 Time Series Forecasting using Deep Learning

A deep learning–based approach to forecasting temporal data using MLP, CNN, LSTM, and hybrid CNN-LSTM architectures.

📘 Overview

This project focuses on building and comparing multiple deep learning models for time series forecasting.
It aims to capture temporal dependencies, trends, and seasonality using modern neural network architectures.

The models are evaluated using real-world sales data from Kaggle competitions, with metrics like RMSE and MAPE.

🗂️ Dataset

The following datasets were used for experimentation:

Predict Future Sales (Kaggle)

Store Item Demand Forecasting Challenge

Data Fields:

Field	Description
shop_id	Unique identifier of shop
item_id	Unique identifier of product
item_cnt_day	Number of products sold
item_price	Current price of an item
date	Sale date (dd/mm/yyyy)
date_block_num	Month number (Jan 2013 = 0)

🕒 Time Range: 2013-01-01 → 2017-12-31

⚙️ Implementation

Libraries Used:

NumPy, Pandas, TensorFlow, Scikit-learn, Matplotlib, Seaborn


Model Architectures Implemented:

🔹 Multilayer Perceptron (MLP) – baseline dense model

🔹 CNN Model – captures short-term dependencies

🔹 LSTM Model – captures sequential patterns and long-term memory

🔹 CNN-LSTM Hybrid – combines spatial and temporal feature learning

📊 Model Performance
Model	Train RMSE	Validation RMSE
MLP	18.36	18.50
CNN	18.62	18.76
LSTM	19.98	18.76
CNN-LSTM	19.20	19.17
📈 Visualizations

Visual exploration includes:

Daily sales trends

Item-level and store-level sales analysis

Model comparison charts

(Add your image links here if available, e.g. /output/sales_trend.png)

🧩 Lessons Learned

Handling seasonality and trends in time series

Feature engineering using window-based sampling

Comparative study of deep learning architectures for forecasting

Use of RMSE/MAPE metrics to evaluate performance

👤 Author

Roshan Prakhar
📍 Ranchi, Jharkhand, India
📧 roshanprakhar@gmail.com

🌐 Portfolio
 • LinkedIn
 • GitHub
