# Stock-Market-Trading-Using-RL-Agent-
Reinforcement Learning Based Trading Algorithm
# Stock Market Trading Using RL Agent

This project implements a Reinforcement Learning (RL) agent for stock market trading, designed to optimize portfolio allocation using historical data. The agent is trained to maximize returns using a reward mechanism based on the Sharpe Ratio, making investment decisions over time.

## Features
- **Reinforcement Learning Agent**: Learns optimal investment strategies through cumulative rewards.
- **Sharpe Ratio Optimization**: Evaluates and rewards decisions based on the Sharpe Ratio.
- **Efficient Portfolio Management**: Utilizes PyPortfolioOpt for portfolio optimization.
- **Backtesting**: Trained on 21 years of historical monthly data and tested on a 3-year period.
- **Visualization**: Comprehensive performance visualizations of rewards, returns, and investment weights.

```

## Requirements
Ensure you have Python 3.8+ installed. Install the required packages using the following command:

```bash
pip install -r requirements.txt
```

Contents of `requirements.txt`:
```
pandas
numpy
matplotlib
PyPortfolioOpt
```

## Project Workflow
1. **Data Preprocessing**: Extracts 12-month rolling data for each year.
2. **Cumulative Return Calculation**: Computes yearly cumulative returns for stocks.
3. **Reward Calculation**: Compares Sharpe Ratio-based returns with actual returns.
4. **Investment Vector Update**: Adjusts the investment vector using a learning rate and exploration factor.
5. **Testing**: Evaluates performance over a 3-year test period.
6. **Visualization**: Generates plots comparing Sharpe Ratio returns vs. actual returns.

## Results
- Trained on **21 years** of historical stock data.
- Tested on **3 years** of unseen data.
- Achieved competitive returns using the RL agent, comparable to the Sharpe Ratio-optimized portfolio.
- Visualized cumulative rewards and portfolio allocations over time.

## Visualizations
- Sharpe Ratio Returns vs. Computed Returns
- Reward Over Time
- Cumulative Return Over Time
- Investment Weights by Sector

![image](https://github.com/user-attachments/assets/f18af6c0-3134-4683-92a3-ff880f2b47cb)
![image](https://github.com/user-attachments/assets/61ca7042-8c2d-4042-a31d-acbde16e4eae)


