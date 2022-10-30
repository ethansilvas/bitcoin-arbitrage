# Module 3 Challenge - Bitcoin Arbitrage

This is a time series analysis of potentially profitable arbitrage opportunities between Bitstamp and Coinbase 
closing price data from 1/1/2018 to 3/31/2018. The analysis looks at the full length data to see if there are any possible trends in the amount
and average return of profitable arbitrage trades. It also looks at specific data from a single date in the early, middle, and later portions of the 
datasets. 

[Bitstamp](/Resources/bitstamp.csv) <br>
[Coinbase](/Resources/coinbase.csv)

---

## Technologies

This is a Python 3.7 project ran using a JupyterLab in a conda dev environment. 

The following dependencies are used: 
1. [Jupyter](https://jupyter.org/) - Running code 
2. [Conda](https://github.com/conda/conda) (4.13.0) - Dev environment
3. [Pandas](https://github.com/pandas-dev/pandas) (1.3.5) - Data analysis
4. [Matplotlib](https://github.com/matplotlib/matplotlib) (3.5.1) - Data visualization


---

## Installation Guide

If you would like to run the program in JupyterLab, install the [Anaconda](https://www.anaconda.com/products/distribution) distribution and run `jupyter lab` in a conda dev environment.


---

## Usage

The provided Jupyter notebook [crypto_arbitrage.ipynb](/crypto_arbitrage.ipynb) will provide all steps of the data collection, preparation, and analysis. Data visualizations are shown inline and accompanying analysis responses are provided. 

---

## Contributors

[Ethan Silvas](https://github.com/ethansilvas)

---

## License

This project uses the [GNU General Public License](https://choosealicense.com/licenses/gpl-3.0/)