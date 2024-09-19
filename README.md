
# Monte Carlo Intraday Risk Simulation

A robust, scalable framework for intraday stock analysis applicable to all equities. By extracting 5min/1min historical data and calculating key statistical measures like mean returns and volatility, we simulate thousands of future price paths using __Geometric Brownian Motion__.    

- This enables real-time computation of critical risk metrics such as **Value at Risk (VaR) & Expected Shortfall** which enhances risk management capabilities.    

- Additionally, we estimate the probability of a stock closing below a specified price threshold, this provides an actionable insight for trading strategies. This approach is fortified with visual analytics to support informed decision-making at the executive level.


## Installation

Libraries needed:

```
pip install yfinance
pip install pandas
pip install numpy
pip install matplotlib
```

or

```
pip install yfinance pandas numpy matplotlib
```

Conda:
```
conda install -c conda-forge yfinance 
```