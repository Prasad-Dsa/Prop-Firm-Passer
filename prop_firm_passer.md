# Prop Firm Passer
NOW IMPROVED. **The Prop Firm Passer** is a multi-symbol EA designed to pass prop firm challenges in the quickest time without using Martingale, Grid and other risky tactics. The EA works on ANY prop firm (FTMO, 5ers, FundedNext etc) and can also be used in funded accounts for making a fixed profit target. The EA uses diversification which is a tried and tested industry standard of reducing drawdown without compromising returns. The EA trades three symbols at once, taking good quality high risk-reward trades and automatically spreads the risk across the three symbols to pass the challenge in the quickest time possible without hitting the DD limit. 

Only one position for each symbol with SL and TP all the time. All results are obtained using **100% quality Real Ticks**.

> NO GRID, NO MARTINGALE, NO ADDING TO LOSERS

Pass your challenges just the way pros trade and manage risk like professional portfolio managers. Simply enter your Profit Target, Max DD and Symbols to trade and let the EA pass your challenge for you.

## Instructions
1. Select any three symbols from the recommended list below or any of your choice and enable them in your Market Watch.
2. Attach the EA to any one of the three Symbols on any timeframe chart. (M1, D1, H1 etc)
2. Enter the symbol names in the inputs as it appears in the Market Watch. Eg: If you want to trade GBPJPY and the symbol appears as GBPJPYx in the Market Watch, then enter GBPJPYx.
3. Enter the Mode and Start Hour for each symbol. The Start Hour is based on the time in your Market Watch (recommended settings below).
4. Enter the Profit Target you want to achieve and Max DD. If you have a daily drawdown limit, enter this value in the Max DD input field. 
5. Run the EA, it will stop trading once the Profit Target is reached to protect the gains.

## Recommended Symbols

|Symbol | Mode | Start Hour |
|-------|------|:---------:|
|XAUUSD | LONG | 01|
|USTEC| LONG | 03 |
US500| LONG| 02 |
DE40 |LONG | 10|
GBPCAD | LONG|03|
GBPJPY|LONG|10|
USDCAD|LONG|12|
XTIUSD|LONG|13|
USDCHF|LONG|13|
EURUSD|SHORT|09|
AUDJPY|SHORT|14|
GBPUSD|SHORT|08|
AUDUSD|SHORT|02|
NZDUSD|SHORT|11|


## Input Parameters
- **Profit Target %:** The profit target you want to achieve. The EA will automatically close all positions once the target is reached.
- **Max Drawdown %:** The Max DD of the challenge. If you have a Max Daily limit enter this value instead of the absolute DD.
- **Symbols to Trade:** The name of the symbol you wish to trade as it appears in the Market Watch. Atleast one symbol needs to be mentioned for the EA to work.
- **Mode:** LONG, SHORT and STRAT mode are available based on the trading direction. STRAT mode takes both long and short trades.
- **Speed:** FAST, MEDIUM and SLOW based on the time required to pass the challenge. FAST mode is recommended.
- **Magic Number:** To uniquely identify trades placed by this EA. Useful when running multiple EAs.

### Troubleshooting Tips
The main idea behind the EA is diversification. However sometimes even uncorrelated symbols can exhibit short term correlation during which the EA may not perform as expected. In such case change the combination of symbols you are trading or choose other symbols from the recommended list.

## Images

![](10_5_1.1_c.png)
![](8_5_1.1_c.png)
![](6_3_1.1_c.png)
![](10_4_1.1_c.png)
![](10_5_1.1.png)
![](8_5_1.1.png)
![](6_3_1.1.png)
![](10_4_1.1.png)


*Risk Disclaimer*

*This EA is designed to maximise your chances of passing the prop firm challenge but does not offer any guarantees as there are many shady prop firms who manipulate the data stream when their users are close to passing. An EA can also make losses. Only trade with money you can afford to lose. The prop firms mentioned are taken as examples and not endorsement.*