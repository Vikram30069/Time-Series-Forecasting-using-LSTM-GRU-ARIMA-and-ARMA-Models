# Time Series Forecasting using LSTM, GRU, ARIMA, and ARMA Models

This project explores time series forecasting techniques using both deep learning models (LSTM and GRU) and traditional statistical models (ARIMA and ARMA). It is implemented in a Jupyter Notebook environment using Python.

## 📊 Dataset
The dataset used is the classic **Airline Passengers Dataset**, which records the monthly total of international airline passengers from 1949 to 1960. It is a univariate time series commonly used for testing time series models.

## Models Implemented

- **LSTM (Long Short-Term Memory)**: A recurrent neural network model capable of learning long-term dependencies in sequence data.
- **GRU (Gated Recurrent Unit)**: A simplified RNN model similar to LSTM with fewer parameters.
- **ARIMA (AutoRegressive Integrated Moving Average)**: A classical forecasting model that combines autoregression, differencing, and moving averages.
- **ARMA (AutoRegressive Moving Average)**: A traditional statistical model using autoregression and moving averages.

## 🧪 Features

- Data cleaning and preprocessing
- Stationarity checks and differencing
- Deep learning model design and training using TensorFlow/Keras
- ARIMA and ARMA implementation using `statsmodels`
- Forecasting and visualization
- Model comparison

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- TensorFlow / Keras
- Statsmodels

## 📈 Output
Each model forecasts future passenger values, and results are compared visually and analytically to evaluate performance.

## 📚 Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/time-series-forecasting-lstm-gru-arima.git
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the notebook in Jupyter or VS Code and run all cells.

## ✅ License

This project is open-source and free to use under the [MIT License](LICENSE).

---
