# QM Pattern Scanner MT4 ReadMe File

This ReadMe file provides a brief overview of the QM Pattern Scanner MT4 code and its functionality. 

## Global Variables
- SymAsk: an array to store the ask prices of symbols
- SymBid: an array to store the bid prices of symbols
- SymTime: an array to store the time of data retrieval
- SymNames: an array to store the names of symbols
- SymTotal: the total number of symbols

## Function Declarations
- ScanMarket(): a function to scan the market and retrieve symbol data
- GetSymbolData(int index): a function to retrieve data for a specific symbol

## Initialization
The OnInit() function is called when the script is initialized. It scans the market and retrieves symbol data using the ScanMarket() function.

## Tick Function
The OnTick() function is called on every tick. It updates the market data using the ScanMarket() function.

## Scanner Function
The ScanMarket() function retrieves the total number of symbols and initializes the necessary arrays. It then loops through all symbols, retrieves symbol data using the GetSymbolData() function, and performs custom analysis on the market data.

## Get Symbol Data Function
The GetSymbolData(int index) function retrieves the symbol name, ask and bid prices, and the current time for a specific symbol.

Please note that ForexRobotEasy is not the official developer of this product. This code is a sample that can work as described in the product. For detailed reviews and trading results of the QM Pattern Scanner MT4, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/qm-pattern-scanner-mt4-review-one-click-multi-timeframe-forex-scan/).

For more information about the official developer of this product, please refer to MQL5.

Backlink: [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/qm-pattern-scanner-mt4-review-one-click-multi-timeframe-forex-scan/)
