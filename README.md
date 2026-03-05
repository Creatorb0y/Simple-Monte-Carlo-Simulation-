# Simple Monte Carlo Simulation 📈
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Creatorb0y/Simple-Monte-Carlo-Simulation-/blob/main/monte_carlo_sim.ipynb)

## Project Overview
This Python script runs a **Monte Carlo simulation** to predict potential stock price paths over a 252-day trading year. It uses 1,000 independent trials to create a probability distribution of final prices.

## Key Features
* **Stochastic Risk Modeling:** Includes a 2% "Black Swan" probability where the market can crash.
* **Volatility Scaling:** Uses the "Square Root of Time" rule to convert annual volatility (28%) into daily fluctuations.
* **Path Dependency:** The model tracks price changes daily, allowing for bankruptcy checks if the price hits $0.

## How to Run
Click the **"Open in Colab"** badge above to run the simulation directly in your browser!
If this does not work then open your preffered notebook and copy and paste the code to see the magic happen!
