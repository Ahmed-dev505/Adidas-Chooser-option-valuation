# Adidas-Chooser-option-valuation
### First  i used adidas five years (2016: 2020) stock prices to make predictions for the first 6 months of 2021 . I want to test how efficient the Discrete-time Geometric Brownian Motion is in predicting the first 6 months of 2021 adidas stock price. i retrieve the five years historical data and apply the GBM. Thereafter, i will make a plot to visualize the error between the predicted first 6 months of 2021  stock price and the actual  first 6 months of 2021 stockprice. This will help us to understand that the descrete-time GBM isn't a perfect stock price prediction tool. Though it is helful in giving us insights on the possible paths that the stock price can follow.
### I will  assume that addidas share price follows a GBM , and the option contract is a european call contract 
### Amsterdam Listed Stock Options 
### CONTRACT SIZE	: One option normally equals rights over 100 underlying shares.
### PRICING UNIT/QUOTATION	 : Euros per share
### OPTION STYLE	: European style Holders of long positions are entitled to exercise their options on the expiration date. 
### DATE OF EXPIRATION	: 1/07/2021
### Doing the valuation via Black-Scholes (BS) model  :

#### Computing The  exotic option which allow the holder to decide the option will be a call or put  at some predetermined future date.In a simple case, both put and call option are plain vanilla option.The value of the simple chooser option is \eqn{\max{C(S,K,t_1),P(S,K,t_2)}}.
