# Nadex ROI Calculator
ROI Calculator for Nadex orders: https://docs.google.com/spreadsheets/d/1ICAVhjvYxdl7GOB5we2qkhbwuMmdd3Bbu9_vOt243Os/edit#gid=496834221

## Definitions
Nadex takes $1 commission to open a position. If the position wins, Nadex takes another $1 commission. If it loses no commission is taken.
* `Buy  Win amount  = (100 - BuyPrice - 2) * NumberOfContracts`
* `Buy  Loss amount = (BuyPrice + 1) * NumberOfContracts`
* `Sell Win amount  = (SellPrice - 2) * NumberOfContracts`
* `Sell Loss amount = (100 - SellPrice + 1) * NumberOfContracts`
* `ROI = Win amount / Loss amount`

## Use

### Table
In the Table sheet you see:
* the number of contracts
* how much you will win or lose if you buy or sell a certain number of contracts
* the ROI for certain buy and entry prices

![text](https://i.imgur.com/kgVDqn2.png "")

### Compare

In the Compare sheet you can compare the ROI of two trades by:
* by changing the number of contracts and buy/sell prices.

![text](http://i.imgur.com/T4IikoS.png "")

## Insights
* Breakeven is if you Buy@48/49 or Sell@52/51.
* Buy@50 or Sell@50 gives 94% ROI.
* Buy@32 or Sell@68 gives 200% ROI.
* Buy@45 has 50% better ROI than Buy@55. Sell@55 has 50% better ROI than Sell@45.

## Disclaimer
* Nadex is a trademark of the Nadex.com exchange.
* None of the information here is approved or supported in any way by the Nadex.com exchange.
* This information is shared to the best of the author's knowledge and is distributed "AS IS" without warranties of any kind, either express or implied. The author is not a financial advisor and cannot be held responsible for any trading losses or other damages incurred as a result of using any information gathered through this website.
