# Bitcoin Price Time Series Analysis and Forecasting Using Prophet
This project involves the time series analysis and forecasting of Bitcoin prices using the Prophet library. Prophet is a forecasting tool developed by Facebook that is particularly effective for time series data that exhibit patterns on different time scales.


#Introduction
This repository contains code and resources for analyzing historical Bitcoin prices and predicting future trends using the Prophet library. The goal is to provide accurate forecasts that can be used for financial analysis and decision-making.

# Installation
To run this project, you need to install the following libraries:

- pandas
- numpy
- matplotlib
- prophet
  
You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib prophet
```
Data Collection
Bitcoin price data can be collected from kaggle [dataset](https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrency-historical-prices-coingecko?select=bitcoin.csv)

Data Preprocessing
Before using the data for forecasting, some preprocessing steps are necessary:

Load the data using pandas.
Convert the Date column to datetime format.
Rename the columns to ds (date) and y (price) as required by Prophet.
python
Copy code
import pandas as pd

References
Prophet Documentation
Pandas Documentation
Matplotlib Documentation
License
This project is licensed under the MIT License. See the LICENSE file for details.
