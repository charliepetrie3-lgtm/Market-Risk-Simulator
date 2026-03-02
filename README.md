# Market-Risk-Simulator
Monte Carlo Stock Simulation: AAPL vs. S&P 500
This project uses Monte Carlo Simulations to forecast the potential future value of an investment in Apple (AAPL) compared to the S&P 500 Index (^GSPC). By leveraging historical price data, the script simulates thousands of possible price paths to calculate risk metrics like Value at Risk (VaR) and Conditional Value at Risk (CVaR).

## Project Overview
The simulation models the final value of a $50,000 investment over a 252-trading day period (1 year). 

Key Metrics Calculated:
Win Probability: The percentage of simulations where the final value was higher than the initial investment.

95% VaR (Value at Risk): The maximum expected loss over a year at a 95% confidence level.

95% CVaR (Expected Shortfall): The average loss in the worst 5% of cases.

Average Win: The average profit across all "winning" (profitable) simulations.

## Technologies Used
Python 

yFinance: To fetch real-time and historical market data.

Pandas & NumPy: For data manipulation and vectorized mathematical operations.

Matplotlib: For visualizing the distribution of simulation outcomes.

## Findings Summary
Metric:
print()
Apple (AAPL), S&P 500 (^GSPC)
print()
Win Probability = 77.05% , 72.64%
print()
Avg. Win (Profit) = $22,873 , $11,951
print()
95% CVaR (Avg. Loss) =  $16,675 , $12,207

## Insight
While Apple boasts a much higher Avg. Win, it comes with a more severe loss of $16,675, which is roughly $4000 more than the S&P. 
