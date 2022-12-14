# Crypto-Arbitrage
This Python application considers arbitrage opportunities in Bitcoin and other cryptocurrencies. As Bitcoin and other cryptocurrencies trade on markets across the globe, the Crypto Arbitrage application identifies arbitrage opportunities by sorting through historical trade data for Bitcoin on both Bitstamp and Coinbase and capitalizes on simultaneous price dislocations by using the power of Pandas and visualizations from Matplotlib Inline.

# Technologies
This project leverages python 3.7 with the following packages:

JupyterLab - JupyterLab is a web-based user interface designed for data analysis.

pandas - Flexible and powerful data analysis / manipulation library for Python.

matplotlib inline - Comprehensive library for creating static, animated, and interactive visualizations in Python.

# Installation Guide
Before running the application first install the following dependencies.

  pip install jupyterlab
  pip install pandas
  pip install matplotlib

# Sample Code 
  ax = bitstamp_sliced.plot(figsize=(20, 10),color="red", title='Exchange Comparison')
coinbase_sliced.plot(color="blue",ax=ax)
# Sample plotted graphs 

ax.legend(["Bitstamp", "Coinbase"])
![image](https://user-images.githubusercontent.com/110577831/185345387-c3c9bce8-bd21-4715-8be5-292fcf7bb838.png)
