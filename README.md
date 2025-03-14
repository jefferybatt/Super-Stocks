# Super-Stocks Profile Tool
Stock analysis tool based on Jesse Stine's book, "Insider Buys: Superstock". 

## Instructions
Using the principles outlined in the book, we've create a Stock Profile dashboard in the sheet, "Is it a Superstock". Using a combination of XLOOKUP functions, IF statements, and Conditional Formatting to highlight or flag the stock metrics that do and don't adhere to the principles outlined in Jesse Stine's book Superstocks, or as best approximation as possible, using my own knowledge of Economics and Finance.

The Data in the sheet, "LIVE Stock Data" is from Refinitiv via Excel feature. To refresh the Data go to the Data Tab and click Refresh all. You can also add a new stock ticker to the bottom of the list at anytime and it should auto populate technicals data.
The "Imported Stock Data" tab is data imported from StockAnalysis.com to also get new fundamentals each quarter (after earnings season). Create a watchlist on StockAnalysis.com with the same stock symbols, and match up the fundamentals metrics from the Imported Stock Data sheet in the same column order, which are; (Symbol/ 200 DMA/ Float/ Shares Insiders/ Shares Institution/ Short%/ PS Ratio/ PE Ratio/ PEG Ratio/ OPerating Margin/ Profit Margin/ FCF/ Total Debt/ Debt to Equity/ Rev Growth Q/ Rev Growth YOY/ Rev Growth 3Y/ Rev Growth 5Y/ EPS/ EPS Growth/ EPS Growth 3Y/ EPS Growth 5Y/ Options/ Analyst Count/ IPO Date).

Download to .CSV. Copy and paste the data onto cell A5, in the "Imported Stock Data" Tab and run the Stock_Analysis_Import_Format Macro. And the new data will be automatically formatted into the table.

Add the new symbol into the "Is it a Super Stock" Sheet in cell C2.

As a side note this is an approximation of the prinicples as he doesn't give hard numbers for all metrics, for example Debt/Equity ratio there is no mention of 0.3, and this can vary widely by industry, but this is a pretty good benchmark for most companies. 
## Disclaimer 
This tool is for informational and educational purposes only and does not constitute financial or investment advice. I am not a financial advisor and I may own shares in some of the stocks included in this project. Use at your own risk and conduct your own research before making any invesmtent decisions.
Enjoy!

![Screenshot of Stock Profile Tool](screenshot.png)
