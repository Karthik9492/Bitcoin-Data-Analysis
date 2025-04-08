# Bitcoin Data Analysis
# Dataset Overview
This dataset contains historical price data for Bitcoin (BTC/USDT) from January 1, 2018, to the present. The data is sourced using the Binance API, providing granular candlestick data in four timeframes:

15-minute (15M)

1-hour (1H)

4-hour (4H)

1-day (1D)

This dataset includes the following fields for each timeframe:

Open time: The timestamp for when the interval began.

Open: The price of Bitcoin at the beginning of the interval.

High: The highest price during the interval.

Low: The lowest price during the interval.

Close: The price of Bitcoin at the end of the interval.

Volume: The trading volume during the interval.

Close time: The timestamp for when the interval closed.

Quote asset volume: The total quote asset volume traded during the interval.

Number of trades: The number of trades executed within the interval.

Taker buy base asset volume: The volume of the base asset bought by takers.
Taker buy quote asset volume: The volume of the quote asset spent by takers.
Ignore: A placeholder column from Binance API, not used in analysis.
