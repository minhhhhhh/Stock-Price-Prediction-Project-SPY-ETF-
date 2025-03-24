# Stock Price Prediction Project (SPY ETF)

This project is a comprehensive stock price prediction tool built using Python, Alpha Vantage API, and LSTM neural networks. It analyzes historical data from the SPY ETF (S&P 500 ETF Trust) to visualize trends, train a predictive model, and provide insights like expected returns.

## Features

- **Fetches SPY historical data** using Alpha Vantage API.
- **Cleans and structures data** into a time series format.
- **Plots SPY closing price trends** over time.
- **Trains an LSTM model** to predict future prices based on historical data.
- **Evaluates model performance** with training and validation loss graphs.
- **Predicts future stock prices** based on user input.
- **Calculates potential investment returns** — input an amount and a past year, and the program computes the expected return in 2025.

---

## Installation

### Prerequisites
Ensure you have Python installed (preferably 3.8 or higher) and install the following libraries:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow alpha_vantage
```

### Clone the Repository
```bash
git clone https://github.com/yourusername/stock-price-prediction.git
cd stock-price-prediction
```

### Alpha Vantage API Setup
1. Get a free API key from [Alpha Vantage](https://www.alphavantage.co/support/#api-key).
2. Replace `API_KEY = "YOUR_API_KEY"` in the script with your key.

---

## How to Run

1. Open the notebook (`Stock_Prediction_Enhanced.ipynb`).
2. Ensure the API key is correctly configured.
3. Run all cells sequentially.

### Expected Workflow
- The script fetches SPY ETF data.
- It processes and scales data for model training.
- The LSTM model trains on historical prices.
- After training, the script saves the model (`advanced_spy_prediction_model.h5`).
- A plot shows training and validation loss.
- It allows you to predict future prices and calculate expected returns.

---

## File Structure

```
/stock-price-prediction
│
├── Stock_Prediction_Enhanced.ipynb    # Main script
├── advanced_spy_prediction_model.h5    # Saved LSTM model
└── README.md                            # This file
```

---

## Example Output

### Closing Price Trend
![Trend Plot](https://via.placeholder.com/800x400?text=Trend+Plot)

### Model Loss Visualization
![Loss Plot](https://via.placeholder.com/800x400?text=Loss+Plot)

### Investment Return Calculation
Example:
```
If you invested $1000 in SPY in 2015, your return in 2025 would be approximately $4873.27.
```

---

## Future Improvements
- **Support multiple stock symbols**.
- **Enhance model architecture** for better predictions.
- **Implement error handling** for API issues.
- **Add user interface** for easier interaction.

---

## License

This project is open-source under the [MIT License](LICENSE).

---



