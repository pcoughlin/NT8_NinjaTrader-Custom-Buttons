(C#) For the semi-discretionary trader, there is a feature lacking in NinjaTrader which is easily remedied with a little C# code: customizable buttons to trigger strategies.  
If you watch the charts to initiate a trading decision but use complex entry, positioning and stop methodology, being able to trigger a strategy manually may be of great use.  
For example, you can create two buttons tied to a dynamic strategy that buys a tick above the high or sells a tick below the low of the last closed bar. 
Before sending out the order, you can calculate the size dynamically according to the market, buying power, and/or size of the signal bar. 
Caution! This code will send orders in NT, do not use if you don't know what you are doing!! 
This is as is, the risk is yours.
