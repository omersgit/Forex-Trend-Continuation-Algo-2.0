# Forex-Trend-Continuation-EA-2.0

Crated using C++ (MQL4)

ALGORITHIM TAKES IN 3 PARAMETERS double input lotsize = X; //Lot Size int SLPips=20;//Stoploss Pips; TPPips=30;//Takeprofit Pips; and Trend continuation pips in either direction

The EA runs on the 1H time frame and executes and reopens trades based on 5 min timeframes. This can be altered in the file by just changing the '5 Min' Interval to choice of preferance.

EA moves x amount of pips in a certain direction, then executes a position in the opposite  trend to subsidize on the move up (BUY) or down (SELL). Once price reaches X amuont of pips in either continous direction it will then continue x amount of pips in the opposite direction and set the current position to breakeven.

With a Stop Loss of X amount of pips and a TP with X amount the EA is able to create a solid R:R ratio to capilaize on trades and therefore grow any trading account in a steady rate.
