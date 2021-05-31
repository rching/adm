# Implementation of ADM algorithm in TD Ameritrade ThinkOrSwim Script 

*Yellow arrow is the rebalance signal*
* +ve signal: Exit  ex-US small cap ETF -> SP500
* -ve signal: Exit  SP500 -> ex-US small cap ETF
* zero line : Exit  ALL -> long term US Treasury 

*10 year backtest with RSI data*
![TD simulation](https://github.com/rching/adm/blob/master/adm-td.png)


reference : https://engineeredportfolio.com/2018/05/02/accelerating-dual-momentum-investing/

Backtest : https://www.portfoliovisualizer.com/test-market-timing-model#analysisResults
