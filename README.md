 Simple Monte Carlo Simulation Description 
 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Creatorb0y/Simple-Monte-Carlo-Simulation-/blob/main/monte_carlo_sim.ipynb)

This Python script runs a simulation to predict potential stock price paths over a 252-day trading year. It uses 1,000 trials to create a probability distribution of final prices.

This model includes a 2% "Black Swan" probability where the market can crash.
this model also uses the "Square Root of Time" rule to convert annual volatility (28%) into daily fluctuations.
The model tracks price changes daily, allowing bankruptcy to occur during the trial

How to Run:

Click the "Open in Colab" badge above to run the simulation directly in your browser!
If this does not work then open your preffered notebook and copy and paste the code to see the magic happen!
