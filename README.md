# Algorithmic_Trading
This will contain all the files required and my notes for the Mannning LiveProject - Algorithmic Trading with Machine Learning.

## 1. Setting Up Your Environment and Sourcing the Data

### Set up the zipline Python environment.

Zipline is a Pyton library to backtest trading strategies.  The setup was mostly handled by the provided liveproject.yml.
Quandl hosts financial data.  The WIKI_PRICES.csv file was downloaded.


The first deliverables were 2 Jupyter notebooks:
1. zipline_test.ipynb to test out the zipline install.  Built a Python ml4t environment.  Had to run several things in the CLI (terminal) and had to download the Jupyter notebook as an actual Python script (.py).  `zipline ingest -b quandl`  first was to bring in the data.

Then `zipline run -f zipline_test.py --start 2016-01-01 --end 2018-1-1 -o dma.pickel no_benchmark` which ran an example dual moving average cross over algorithm.

2. clean_wiki_stock_data.ipynb was to test manipulation of data.  First had to download WIKI_PRICES.csv (huge file) from Quandl with my API key.

Learned a few Python things - commented in the notebook.


