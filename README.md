<!-- PROJECT HEADER -->
<h1 align="center">🧠 Time Series Forecasting using Deep Learning</h1>

<p align="center">
  <b>Predicting future sales trends with MLP, CNN, LSTM, and Hybrid CNN-LSTM models</b>  
  <br/>
  <a href="https://github.com/Roshan-prakhar/machine-learning-1"><strong>Explore the docs »</strong></a>
  <br/>
  <br/>
  <a href="https://github.com/Roshan-prakhar/machine-learning-1">View Demo</a>  
  ·  
  <a href="https://github.com/Roshan-prakhar/machine-learning-1/issues">Report Bug</a>  
  ·  
  <a href="https://github.com/Roshan-prakhar/machine-learning-1/issues">Request Feature</a>
</p>

---

<p align="center">
  <img src="https://github.com/Roshan-prakhar/machine-learning-1/blob/main/assets/banner.png?raw=true" alt="Project Banner" width="800px">
</p>

---

## 🌟 Project Overview

This repository showcases how **Deep Learning** can be applied to **Time Series Forecasting** tasks to predict sales, trends, or demand.  
We compare multiple architectures — **MLP**, **CNN**, **LSTM**, and a **Hybrid CNN-LSTM** — and evaluate their performance using real-world datasets.

The goal is to learn patterns from sequential data, model temporal dependencies, and predict future outcomes effectively.

---

## 📂 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Project Architecture](#-project-architecture)
- [Installation](#️-installation)
- [Data Preprocessing](#-data-preprocessing)
- [Model Training](#️-model-training)
- [Evaluation Results](#-evaluation-results)
- [Lessons Learned](#-lessons-learned)
- [Author](#-author)
- [License](#-license)

---

## 📊 Dataset

We used publicly available Kaggle datasets:

- [Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales)
- [Store Item Demand Forecasting Challenge](https://www.kaggle.com/c/demand-forecasting-kernels-only)

**Duration:** `2013-01-01 → 2017-12-31`

| Feature | Description |
|----------|--------------|
| shop_id | Unique identifier for a shop |
| item_id | Unique identifier for a product |
| item_cnt_day | Number of items sold per day |
| item_price | Current price of an item |
| date | Date of sale |
| date_block_num | Month index (Jan 2013 = 0) |

---

## 🏗️ Project Architecture

