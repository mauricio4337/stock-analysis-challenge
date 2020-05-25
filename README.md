# Challenge

## Summary of Macros and Results

* AllStocksAnalysis() Macro code created from module work to be refactored
* totalVolume, startingPrice, and endingPrice variables replaced by arrays
* tickerIndex variable created to access each array value corresponding to a given ticker 0 --> AY, 1 --> CSIQ, etc.
* Nested loop in original code is replaced with a single loop that is more efficient.
* A second loop is used to output the analysis to the All Stocks Analysis worksheet, although the output could have been included in the previous loop.
* Formatting for the All Stocks Analysis worksheet and the ClearWorksheet() macro are the same as before.
* The collection and output of analysis values is more efficient becuase it loops through the data only once instead of 11 times.
