# Stock Market Predictor App

This repository contains the code for a **Stock Market Predictor App** built using Streamlit, with a machine learning model trained on historical stock data fetched using `yfinance`. The app provides predictions for future stock prices, along with visualizations of stock trends, helping users make informed decisions.

The app has been deployed on Render and is accessible at: [Stock Market Predictor on Render](https://stock-market-predictor-1-jy9o.onrender.com)

---

## Features

- **Real-Time Stock Price Prediction**: Input a stock ticker symbol to get predictions for future stock prices based on historical data.
- **Historical Data Visualization**: Interactive graphs to visualize past stock price trends.
- **Neural Network-Based Predictions**: Predictions are made using a Keras-trained neural network model.
- **User-Friendly Interface**: The app is designed with a simple and intuitive interface using Streamlit.

---

## Live Demo

Try the app live: [Stock Market Predictor on Render](https://stock-market-predictor-b7dp.onrender.com)

---

## Installation

To run this app locally on your machine, follow the instructions below:

### 1. Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/stock-market-predictor.git
cd stock-market-predictor
```

### 2. Install Dependencies

Install the required Python libraries using the requirements.txt file:

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App

Once the dependencies are installed, you can run the app:

```bash
streamlit run app.py
```
This will start a local development server, and the app will be available at http://localhost:8501

---

## Requirements

The project depends on several Python libraries, which are listed in the requirements.txt file:

- numpy
- pandas
- matplotlib
- yfinance
- keras
- streamlit

You can install these dependencies via:

```bash
pip install -r requirements.txt
```

---

## Model Creation

The stock market predictor model was created using a neural network built with Keras, trained on historical stock data obtained using yfinance.

- The data is fetched using yfinance and preprocessed for model training.
- The model is built and trained in the Jupyter notebook: Stock_Market_Prediction_Model_Creation.ipynb.
- The trained model is used in the Streamlit app to make predictions on future stock prices.

---

## How It Works
- The user enters a stock ticker symbol (e.g., AAPL, TSLA) into the app.
- The app fetches historical stock data for that ticker using the yfinance API.
- The neural network model predicts future stock prices based on the historical data.
- The app displays the predictions along with interactive visualizations of historical stock price trends.

---

## Deployment
The app has been deployed on Render. If you'd like to deploy the app yourself, follow these steps:

### Render Setup
- Create an account on Render.
- Set up a new Web Service in Render.
- Connect your GitHub repository to Render.
- Render will automatically build and deploy your Streamlit app.

---

## Contributing
Contributions are welcome! If you have any suggestions or bug reports, feel free to open an issue or submit a pull request.

---
