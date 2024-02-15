# TS Prop Firm ReadMe File

This ReadMe file provides a brief overview of the code for the TS Prop Firm trading system. Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Introduction
TS Prop Firm is a tailored forex software designed for prop trading firms. It aims to provide a customizable and efficient trading solution for traders. This code provides the necessary functionality to manage risk levels and enable a news filter to avoid trading during high-impact news events.

## Developer's Site
For detailed reviews and trading results of this product, please visit the developer's website at [https://forexroboteasy.com/forex-robot-review/ts-prop-firm-mt4-review-tailored-forex-software-for-prop-trading-firms/](https://forexroboteasy.com/forex-robot-review/ts-prop-firm-mt4-review-tailored-forex-software-for-prop-trading-firms/).

## Input Parameters
The code allows users to customize the following input parameters:

- RiskLevel: Defines the risk level for trading (1-Low, 2-Medium, 3-High).
- NewsFilter: Determines whether to enable the news filter.

## Trading Symbols
The code supports three trading symbols:

- EURUSD
- XAUUSD
- US30

## Expert Functions
The code includes the following expert functions:

1. OnInit(): This function is called during expert initialization and sets up the news event filter if enabled.
2. OnDeinit(): This function is called during expert deinitialization and removes the news event filter if enabled.
3. SetNewsFilter(): This function sets the news event filter based on the current hour and high-impact news events occurring within 60 minutes.
4. RemoveNewsFilter(): This function removes the news event filter for the specified symbols.
5. OnTick(): This function is called on each tick and executes the trading logic based on the defined risk level.

## Trading Logic
The trading logic in the code is based on the selected risk level. The following logic is implemented for each risk level:

- Low Risk (RiskLevel = 1): No specific logic is provided. Users can customize this section based on their low-risk trading strategy.
- Medium Risk (RiskLevel = 2): No specific logic is provided. Users can customize this section based on their medium-risk trading strategy.
- High Risk (RiskLevel = 3): No specific logic is provided. Users can customize this section based on their high-risk trading strategy.

## Usage
To use this code, follow these steps:

1. Customize the input parameters (RiskLevel, NewsFilter) according to your trading preferences.
2. Modify the trading logic in the OnTick() function based on your risk level.
3. If desired, modify the trading symbols to match your preferred trading instruments.
4. Compile the code and apply the expert advisor to your MT4 platform.

## Conclusion
TS Prop Firm is a powerful forex software designed for prop trading firms. This code provides a sample implementation of its functionality, allowing users to manage risk levels and enable a news filter. For detailed reviews and trading results, please visit the developer's website mentioned above.
