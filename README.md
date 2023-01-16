# S&P 500 Portfolio Optimizer 
This repository contains a Jupyter notebook that utilizes the IEX Cloud API to gather data on the S&P 500 companies and the Interactive Brokers API to execute trades based on user-specified portfolio size. This notebook is a modified version of the original work by Nick McCullum - https://github.com/nickmccullum/algorithmic-trading-python 
## Getting Started 
1. Clone the repository to your local machine. 
2. Install the required packages listed in the requirements.txt file. 
3. Obtain an API key for both IEX Cloud and Interactive Brokers. 
4. Replace the placeholder values in the notebook with your own API keys. 
5. Run the notebook to gather data on the S&P 500 companies and determine the optimal number of shares to purchase for each company based on your portfolio size. 
6. Note the current version of the code is only buying one stock and the full shares to buy feature is yet to be implemented. 
## Built With 
IEX Cloud API - Used to gather data on S&P 500 companies 
Interactive Brokers API - Used to execute trades based on data gathered by IEX Cloud 
## Authors 
Daniel - Modification And trading bot. 
## WARNING: 
This code is intended for educational and testing purposes only. Do not use it on a real Interactive Brokers account as it may result in unexpected and potentially harmful trades. Always test and verify the code on a virtual or sandbox environment before using it on a real account.
