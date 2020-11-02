# Frequently Asked Questions

*** 
> *How to use this FAQ Section*
**Use the search bar above! OR use the search function in your browser. "CMD +f" is your friend here! Simply search for what you're looking for to find the answer.**

### Why did my indicator not send a buy or a sell when the market price changed?

If you're experiencing this, you may be using the tool for the wrong reasons. -If you were confused as to why it has not sent a buy or sell signal, there are two options-
The buy and sell criteria was not triggered for a good reason. This is not a bug and you are misinterpreting the use of this tool.
You can choose to make your own buys and sells without using the indicator. Just now there is a good reason the alert didn?t fire

### A MarketGod Alert was sent to my phone / email but nothing painted on the chart when I looked

*This is an easy fix and is typically caused by one of two issues*
1. Your alerts are outdated
   - When we publish a new update, we recommend you reset your alerts entirely. There are tools we recommend to make this an easier process, but it must be done. We ask this because Tradingview does not automatically update the alerts that are already set, when you add a newer version of the chart. So in essence, you're receiving a ghost alert from an older version of MarketGod

2. You are using a very low time frame and the alerts are not confirmed when you check
   -  MarketGod calculated IN REAL TIME. Meaning, the algo fires the signals when the current bar meets a preset criteria. On lower-time frames, this means there are likely calculations taking place that are right on the edge of hitting the pre-established criteria. We do this as an effort to justify our integrity in calculating without repainting. Our recommendation is the wait until the alert is CONFIRMED before evaluating the signal.-

### What is Repainting?

Repainting in the forex is a term that represents the trading platform indicator that repainting, meaning that indicator changes display on the chart as new price data (candles/bars) comes in. A repainting process shows that the indicator is displaying on the chart is highly accurate when it is not.

**Repainting indicator**
" The repainting indicator is one that goes on changing in its value as an indicator repositioning its line at the point where the current price bar is forming. Such indicators take the help of future data to bring forth the values and signals for entry. In this way, repainting indicators ensure their exit and entry signals in the past look highly accurate and has zero error. The repainting indicator looks accurate on the chart but in real trading, they are not. Naturally, all Tradingview Programmers writing in pine-script will encounter questions regarding the validity of a given script, and how it handles repainting.For those who may be unfamiliar, here is the direct definition of repainting from the Tradingview Pine-Script Manual
Historical data does not include records of intra-bar movements of price; only open, high, low and close (OHLC). This leads to a script sometimes working differently on historical data and in real-time, where only the open price is known and where price will typically move many times before the real-time bar?s final high, low and close values are set after the real-time bar closes. Strategies using calc_on_every_tick=true. can trigger a repaint warning. Even strategy with parameter calc\_on\_every\_tick = false may also be prone to repainting, but to a lesser degree. Using security for requesting data from a resolution higher than the resolution of the chart?s main symbol can also trigger repainting." 

### Does MarketGod Repaint?

No.

### What Is MarketGod and MarketGod Trading?

MarketGod Trading is an organization committed to better enabling retail traders on their road to success. Our offering is a technical indicator that can be accessed via third party partners, like tradingview.com, to ultimately suggest when our users should buy and sell a given security or financial market.

### Where Can We Buy Access to MarketGod for Tradingview?

**MarketGod For Tradingview**
[Card Payment](https://checkout.marketgod.io)
[Crypto Payment](httos://marketgodx.com/checkout/crypto)

### Which Markets Can I Apply MarketGod On?

We've designed MarketGod to work on all of them. If a ticker is available on our partners site, we can analyze the data and apply the algorithm. This includes, but. is not limited to
- Equities
- Commodities
- FOREX
- OTC
- Cryptocurrencies
- Indexes (Options)
- ETFs & Mutual Funds
  
Ultimately, if you're a fan of finance, we have a solution for you. Our Financial Service is well known and the benefits towards your overall investing success will be clear.

### How Do I Find MarketGod once On Tradingview?

1. From your tradingview chart, access the public indicator library near the top of the screen
2. On the left hand side, you will see a section titled "invite only".
3. If the section is not there, you are not yet on the permissions list
   1.  If you have been waiting for more than 12 hours, please email our team
4. From the invite-only tab in the indicator library, you should see two options
   - MarketGod for Tradingview [study] 
   - MarketGod for Tradingview [strategy]
Select either of the two available options, noting that each is published by user @marketgodx, no longer TVMarketGod

### What Comes With My MarketGod Purchase?

MarketGod for Tradingview Includes
1. MarketGod for Tradingview [study]
2. MarketGod for Tradingview [strategy]

### What Can I Use For Free?

Regardless if you are a MarketGod customer/user, all traders on tradingview.com can access these tools we have published-
- MarketGod Visuals
- Market EKG
- RSI Divergence

###  Do You Accept Crypto Payment

We accept all cryptocurrencies from all countries. By design, you may notice from time to time our cryptocurrency prices are significantly lower than the card payment.-
[Pay with crypto](https://marketgodx.com/checkout/crypto)

###  Is There An Affiliate Program

Yes, Register following this link Affiliate Registration

###  How Are We Supposed To Use MarketGod

[See Tutorials](marketgodx.com/tutorials)

###  How Do We Set Up MarketGod

*Please view our tutorials pages to see the process for adding MarketGod to your Charts*

###  I've Recently Purchased. My Indicator Access Is Still Locked

Please be sure you have provided us with your username for Tradingview so we may add you to the tool.
*If you have Please check you have refreshed your browser, and move on to the nextstep.*

*If you have not Please Email us your order confirmation, along with your Tradingview Username, to admin@marketgod.io* 

### How Long Does it Take to be added to the MarketGod Permissions List

In most cases we will add you within 15 minutes. 
  - We are working to eliminate the long delays, but occasionally system errors could result in 4+ hours to be added. 
    - Weekends and holidays may be slower.
**If you are not on the tool after 12 hours, please email us a reminder**

###  Is there a best time frame to use this tool

View General Uses Section

###  Does the Type of Candle Matter
Not much. All script inputs are taken independent of your chart input.
Just make sure you're not backtesting the strategy with Heikin Ashi. 

### Which Alert Setting is Best? Once Per Bar
Once per bar is correct.
And if you haven't received an alert on the 1D frame yet, that's because the Market isn't offering any trades MarketGod deems as risky worthy. This is a good thing. View the support item on Tradingview Support links for more info.

### It Seems that my Alerts Disappear Before the Period Closes
As mentioned in suggested uses, we advise waiting until the prior period has closed for confirmation.

### May I know how Eric Thies is using it? The settings, and method/strategies
HA Candles. TF's ranging 1h, 4h, 6h, 1D, 3D, 1w, 2w and 1M. Bollinger Bands & Keltner Channels on my chart, with MarketGod Visuals Tool and RSI Divergence. Sometimes I use the BB% Oscillator

### When does MarketGod calculate its signals
The signals are calculated by the most recent data available to the indicator on tradingview. If your chart is in relatime, it will send the alert in real time, meaning AS IT HAPPENS. If your chart is using signals that are delayed, MarketGod will calculate on the data made available time.
For Automation purposes, alerts and notifications send at the confirmation of the period closing with a given alert.
The different classical technical indicators comprised across the various MarketGod versions include magnitudes of various oscillators mainly comprised of MACD, RSI, Stochastic, Ichimoku, Gann Trend Analysis, Wyckoff Accum/Distribution Laws, Fibonacci calculated support/resistances, and more.

### The Lock on My Indicator Access is Still Red
Still try adding the tools after refreshing the browser. The red lock updates once you've accessed a tool, not just gained access to it.

### Why are my labels only showing up on part of the chart?
Seeing this or something similar below on your charts? It may happen when switching between 'plots' and 'labels' due to trading view's limitation on labels that are allowed on a given chart.
Simply put, the more authors with visuals on charts takes more server space and creates slower environments for users. So they limit the visuals to keep the servers as fast as traders need.
To solve this, we recommend changing the time frame, zooming in, or reducing the frequency in alerts by changing the filter settings to a higher number. You may also replace the label options with normal plots again.

### Can I use these indicators with a Free Tradingview account
You can use all of our indicators with a free account, but keep in mind, with a free account you can only set up one live alert and only have up to three indicators on your chart active at one time. With a Pro account, you can set up multiple alerts and have up to 10 indicators on your chart at one time. I recommend a PRO+ account which will give you more than enough alerts and indicators on your chart. 

###  Do you have indicators coded for MT4

Our indicators only work on TradingView at the moment. There are some plans to code them for MT4 and MT5 but we don't have an ETA on that.

What a lot of traders do is chart their trades with our indicators on TradingView and then place their trades on MT4. This is a very popular and preferred method since TradingView is known to have the best charting platform for Crypto, Stocks, and Forex and MT4 is well known for it's fast and easy trade execution platform.

### Why is the Admin in the Discord Group Non-Responsive

Our team chooses to be less involved. This is not a trading group, or premium paid group in which the admin needs to be involved. This is a product, and was purchased.. Questions that are asked will be answered if they are
Unasked, or un-addressed elsewhere in the group
New problems or issues that need a response.
***