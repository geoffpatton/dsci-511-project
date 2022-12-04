# dsci-511-project
DSCI-511 - Final Project - Group 1

## Financial Market Data Store

### Group 1 - Members
- Geoff Patton - gp495@drexel.edu
- Ananda Mahalingam - asm465@drexel.edu
- Fengtian Lu - fl373@drexel.edu
- Rohit Bhattacharya - rb689@drexel.edu

### Project Summary
Our appication will generate real-time and historical financial market data. Our data is gathered form [Finnhub](https://finnhub.io/docs/api). Below is a list of some of data we generate for analysis:
 - __Basic Conpany Financials:__ Includes the basic financials of a company such as margin, P/E ratio, 52-week high/low etc.
   - `basic_company_financials.csv`
 - __Company Profile:__ General information on a company.
   - `company_profile.csv`
 - __Candlestick Data:__ Daily candlestick data (OHLCV) for stocks.
   - `candlestick_data.csv`
 - __Company Surprise Earnings:__ Historical quarterly earnings containing expected and actual earnings
   - `surprise_earnings.csv`
 - __Recommendation Trends:__ The latest analyst recommendation trends for a company.
   - `recommendation_trends.csv`
 - __Insider Sentiment:__ Insider sentiment for companies using the Monthly Share Purchase Ratio (MSPR). To give investors a glimpse at what the executives are thinking about the stock price and valuation in the near future.
   - `insider_sentiment.csv`
 - __Insider Transactions:__ Insider transactions data sourced from Form 3,4,5, SEDI and relevant companies' filings.
   - `insider_transactions.csv`
 - __Social Media Sentiment:__ social sentiment for stocks on Reddit and Twitter.
   - `social_media_sentiment.csv`
 - __Senate Lobbying Activities:__ list of reported lobbying activities in the Senate and the House.
   - `senate_lobbying.csv`
 - __Finanicals as Reported:__ a company's financials as reported including income statements, cash fow, and balance sheets.
   - `balance_sheet.csv`, `cash_flow.csv`, `income_statement.csv`

### Issues and Limitations:
 - Timeouts/Rate Limit – 30API Calls/sec
 - Data Size & Storage
 - Free endpoint options not having as much historical data


### Software Pre-requisites:
```
pip install pandas
pip install finnhub-python
```


### Running instructions 
- Open the final_project_group_one jupyter notebook
- Press `Run All` Button
