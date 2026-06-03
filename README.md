# Gas_Storage_Valuation_Model
A cashflow-based simulation model that values natural gas storage contracts by optimizing injection and withdrawal decisions under price dynamics, storage constraints, and operational costs. The project demonstrates core concepts in energy trading, real options valuation, and commodity risk modeling.
⛽ Natural Gas Trading & Storage Simulation

A Python-based commodity trading simulation that models natural gas storage decisions using historical price data. The project tracks inventory levels, cashflows, and profitability over time to demonstrate the economic principles underlying commodity storage and energy trading.

📌 Overview

Natural gas storage creates value by allowing market participants to buy gas at lower prices, store it, and sell it when prices increase.

This project implements a simplified trading framework that:

Loads historical natural gas prices
Simulates buy/sell decisions based on price movements
Tracks storage inventory dynamically
Computes cumulative Profit & Loss (PnL)
Visualizes strategy performance over time

The objective is to understand how price volatility and inventory management influence the economics of commodity storage.

⚙️ Methodology

At each time step:

If the current price is higher than the previous price:
Buy gas
Increase storage inventory
If the current price is lower than the previous price:
Sell gas
Decrease storage inventory

The model records:

Cash position
Storage level
Cumulative PnL
📊 Visualizations

The project generates several performance dashboards:

1. Natural Gas Price Evolution

Tracks historical market prices over time.

2. Storage Inventory Levels

Shows how inventory changes based on trading decisions.

3. Cumulative Profit & Loss (PnL)

Measures the overall profitability of the strategy.

📈 Example Results

Final PnL: -1950.50

Final Storage Level: 6 units

Key Insight

The strategy generated a negative PnL, highlighting that simple momentum-based trading rules do not necessarily capture optimal market timing. This demonstrates the importance of optimization and risk management in commodity trading.

🔍 Key Concepts Demonstrated
Commodity Storage Economics
Energy Trading Fundamentals
Inventory Management
Time-Series Analysis
Cashflow Modeling
PnL Attribution
Risk & Performance Evaluation
⚠️ Limitations

This project is intentionally simplified and does not include:

Storage capacity constraints
Injection/withdrawal rate limits
Transaction costs
Forward curve modeling
Stochastic price simulation
Dynamic programming optimization
Real options valuation
🚀 Future Enhancements

Potential extensions include:

Dynamic Programming for optimal storage decisions
Monte Carlo simulation of gas prices
Forward curve and seasonality modeling
Storage optimization under operational constraints
Value-at-Risk (VaR) analysis
Real options valuation techniques
🛠️ Tech Stack
Python
Pandas
NumPy
Matplotlib
📚 Learning Outcome

This project bridges financial theory and practical implementation by demonstrating how commodity storage value depends on exploiting temporal price spreads through inventory management and trading decisions.

It serves as a foundation for more advanced energy trading, commodity risk, and quantitative finance models.
