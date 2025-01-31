# RBC Stock Trading Algorithm

Predicts RBC stock prices using Polynomial Regression, with backtesting to evaluate performance. Calculates Sharpe ratio and Max Drawdown for strategy assessment.

## Tech Stack
- Python
- yfinance, Pandas
- Matplotlib, Seaborn
- scikit-learn
- Plotly

## Features
- Fetch real-time RBC stock data.
- Preprocess data, including feature engineering.
- Predict stock prices using Polynomial Regression.
- Backtest the model with real historical data.
- Evaluate the strategy using Sharpe ratio and Max Drawdown metrics.
- Visualize stock price trends.

## Run
1. Clone the repo:
git clone https://github.com/yourusername/RBC-Stock-Trading-Algorithm.git


2. Navigate to the project directory:
cd RBC-Stock-Trading-Algorithm


3. Install dependencies:
pip install -r requirements.txt


4. Run the script:
python main.py


## Example Output
Below is an example of the output that the script will print when run:
- Predicted price for 2025-01-14: 296.57
- Predicted price for 2025-01-15: 296.46
- Predicted price for 2025-01-16: 296.35
- Predicted price for 2025-01-17: 296.26
- Predicted price for 2025-01-18: 296.17
- Sharpe Ratio: -1.85 
- Max Drawdown: -0.67



