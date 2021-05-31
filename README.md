# Implementation of ADM algorithm in TD Ameritrade ThinkOrSwim Script 

*Yellow arrow is the rebalance signal*
* +ve signal: Exit from ex-US small cap ETF -> SP500
* -ve signal: Exit from SP500 to ex-US small cap ETF
* zero line : exit all -> long term US Treasury 

*10 year backtest with RSI data*
![TD simulation](https://github.com/rching/adm/blob/master/adm-td.png)


reference : https://engineeredportfolio.com/2018/05/02/accelerating-dual-momentum-investing/

Backtest : https://www.portfoliovisualizer.com/test-market-timing-model#analysisResults
