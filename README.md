# optionscode
This code backtests the performance of an at-the-money SPY put (sold) and a SPY put (bought) 25 points below, opened every Wednesday from Jan 2022 to May 2022. 

- This file reads from various data sources, TDA Ameritrade (in_tda), CBOE (in_cboe), Yahoo Finance (in_yahoo), combines them into a new df (in_all) and outputs a df called out.
- The backtesting involves running the same trade through many different combinations of variables (DTE, days_to_close, take_prof, take_loss) to find out what was the ideal parameter set, using grid search.
- A total of 7,200 possible combinations were evaluated.
- Once this ideal set of parameters are determined, trades can be placed while monitoring and comparing the performance of future trades to past trades.
- Please contact chuayaocong@gmail.com if you require assistance. Do note that the source files will not be provided due to the large data size (> 3GB).
