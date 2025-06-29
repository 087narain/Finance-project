# Finance-project

# Stock Price Prediction with LSTM

This project uses an LSTM neural network to predict the next-day closing price of Nike (NKE) stock based on historical data (Close, Volume, RSI). It's built in Python using PyTorch, yfinance, and matplotlib.

## What It Does

- Downloads historical data using `yfinance`
- Extracts technical indicators like RSI & Volume
- Trains an LSTM model to predict the next-day closing price
- Evaluates model performance (RMSE, MAE)
- Plots prediction results and error distribution

## Results

Results of the model are shown in the 4 .png files.

## Dependencies

- Python 3.9+
- PyTorch
- NumPy
- Pandas
- matplotlib
- yfinance
- scikit-learn

## How to run:

- Clone repo
- Install dependencies  
- Run in teminal: 
    ```bash
   jupyter notebook main.ipynb

## Things I would improve:

- Inclusion of more variables (such as rate of change)
- Incorporation of external data (effects of supply-side shocks, earnings reports etc.)
- Consideration of impact of competitor stocks as secondary inputs in price determination.
