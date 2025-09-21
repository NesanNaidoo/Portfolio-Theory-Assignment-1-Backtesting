 # Problem Specification
 This assignment investigated the statistics of strategy backtesting. Part I focused on prov
ing that the estimated annualized Sharpe ratio(SR) converges asymptotically to a normal
 distribution. Furthermore, part I motivated that for a sufficiently large number of samples,
 the mean of the sample maximum of standard normally distributed random variables can
 be approximated. Lastly, part I focused on the derivation and discussion of the minimum
 backtest length.
 Part II focused on mean–variance backtesting of the tangency portfolio under full investment
 and no-short-selling constraints. Sharpe ratio–maximising portfolios were calculated from
 rolling windows of the historical data. The historical dataset is divided into in-sample (IS)
 and out-of-sample (OOS) datasets. Two experiments are conducted: 1) compared IS and
 OOS Sharpe ratios and 2) evaluated OOS backtest performance using a rolling window
 approach
 
# Data Specification
 The Tactical Asset Allocation data is loaded from “PT-DATA-ALBI-JIBAR-JSEIND-Daily
1994-2017.xlsx” with the following asset information: \ Key: (Number of rows, number of
 columns) 
 1.  Sheet 1: (8439,2) ALBI (All Bond Index (ALBI) Total Return Index (TRI) Data
 2.  Sheet 2: (8405,4) Money Market Data: JIBAR and STEFI TRI
 3.  Sheet 3: (8439,28) JSE ICB Industrial Level Indices
 4.  Sheet 4: (8439,20) JSE Various Indices: JSE Growth, JSE Value, JSE ALSI, JSE SRI

 # Configuration control
Coding for Part II’s Experiment 1 and 2 was completed using RStudio 2024.09.0+375 (“Cran
berry Hibiscus” Release) and was based on R and MATLAB code provided by Professor Tim
Gebbie(STA4028Z). 

Version control: managed with Git and GitHub.
 
