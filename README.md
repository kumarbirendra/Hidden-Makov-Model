# Stock Price Prediction Using HMM, LSTM, ARIMA, and RNN

This project focuses on forecasting stock prices using four different models: Hidden Markov Model (HMM), Long Short-Term Memory (LSTM), AutoRegressive Integrated Moving Average (ARIMA), and Recurrent Neural Network (RNN). The models are applied to the NIFTY 50 stock index data, and their performances are compared using various error metrics.

## Results

The efficiency of the HMM model was compared against LSTM, ARIMA, and RNN models using the following metrics:

- **APE**: Absolute Percentage Error
- **AAE**: Average Absolute Error
- **ARPE**: Average Relative Percentage Error
- **RMSE**: Root Mean Squared Error

### Efficiency Comparison

| Metric  | HMM vs LSTM Efficiency | HMM vs ARIMA Efficiency | HMM vs RNN Efficiency |
|---------|------------------------|-------------------------|-----------------------|
| **APE** | 0.8780                 | 0.3284                  | 0.8374                |
| **AAE** | 0.8780                 | 0.3284                  | 0.8374                |
| **ARPE**| 0.8780                 | 0.3284                  | 0.8374                |
| **RMSE**| 0.8490                 | 0.3076                  | 0.8293                |

![Results Comparison](https://github.com/Nikhil-Kumar-Patel/Hidden-Makov-Model/blob/main/output.png)

## Conclusion

The Hidden Markov Model (HMM) demonstrated strong performance compared to LSTM, ARIMA, and RNN, particularly in cumulative error metrics like CSPE. This indicates that HMM is effective in capturing long-term trends in stock prices, making it a viable model for forecasting in financial markets.

## How to Run

1. **Install Dependencies**: Ensure you have Python and the necessary libraries installed:
   - `hmmlearn`
   - `numpy`
   - `pandas`
   - `matplotlib`
   - `yfinance`
   - `tensorflow`
   - `scipy`
   - `statsmodels`

2. **Run the Notebook**: Load the provided Jupyter notebook and execute each cell sequentially to train the models and generate predictions.

3. **Analyze Results**: Compare the model performances using the provided metrics and visualize the predicted versus actual stock prices.

## Acknowledgments

This project benefits from the contributions of the open-source community and the developers of the libraries used. Special thanks to all contributors.
