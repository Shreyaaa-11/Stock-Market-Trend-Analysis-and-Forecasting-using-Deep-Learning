# 📈 Stock Market Trend Analysis and Forecasting using Deep Learning

This project implements a deep learning model for **stock price forecasting** using **Gated Recurrent Units (GRU)**, a type of recurrent neural network well-suited for time-series data.  
Historical stock datasets (Google, Microsoft, Amazon, IBM) are used to train and evaluate the model.

---

## 🚀 Project Overview
- **Goal**: Predict future stock prices based on past performance.
- **Problem**: Stock markets are highly volatile, making prediction challenging.
- **Solution**: Use GRU networks to capture temporal dependencies in stock price data and forecast future values.

---
## 📂 Project Structure
    ├── data/ # CSV files for Google, Microsoft, Amazon, IBM (not included)
    ├── results/ # Plots and outputs (optional)
    ├── Stock-Market-Trend-Analysis-and-Forecasting-using-Deep-Learning.ipynb # Main Jupyter Notebook
    └── README.md # Project documentation

---
## 🛠️ Features
- Data preprocessing: cleaning, normalization, and sequence generation.
- Deep learning with PyTorch: GRU-based recurrent neural network.
- Model training and evaluation with **RMSE (Root Mean Squared Error)**.
- Visualizations using Matplotlib, Seaborn, and Plotly:
  - Stock trends over time.
  - Training loss curve.
  - Predicted vs. actual stock prices.

---

## 💻 Technologies Used
- **Python**: Data processing & modeling
- **Pandas, NumPy**: Data manipulation
- **Matplotlib, Seaborn, Plotly**: Visualization
- **PyTorch**: Deep learning framework
- **Scikit-learn**: Metrics and preprocessing

---

