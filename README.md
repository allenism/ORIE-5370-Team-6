# ORIE-5370-Team-6

How to replicate:

1. ftse350_data_features1 & ftse350_data_features2/sp500_data_features1 & sp500_data_features2 are folders of pre-cleaned and processed feature data for stocks in FTSE 350/S&P 500 (raw data are omitted here);
2. data_cleaning_sp500.ipynb is the code used to pre clean the raw data for S&P 500 to the features data, and minor changes can be made in the file for cleaning FTSE 350 stock data;
3. MarketStateEval_ftse350.ipynb/MarketStateEval_sp500.ipynb are codes used to evaluate market regime persistence for all the strategy configurations. The outputted files are MarketStateEvalution_ftse350.csv and MarketStateEvalution_sp500.csv;
4. ftse350_backtest.ipynb & sp500_backtest.ipynb are codes to evaluate all strategy configurations for FTSE 350/S&P 500 data, and the outputted files are in the folders ftse350_backtest/sp500_backtest;
5. ew_comparison.ipynb is the code used to compare the results to the equally weighted portfolio and the outputted files are in the folders ftse350_backtest_ew/sp500_backtest_ew;
6. final_analysis.ipynb is the code used to analyze the peformances in both the entire investment horizon and stock market crises. The output files are in folder ftse350_final_result/sp500_final_result
