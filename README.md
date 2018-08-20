# stock-market
Our aim is to create software that analyzes previous stock data of certain companies, with help of certain parameters that affect stock value. We are going to implement these values in data mining algorithms and we will be able to decide which algorithm gives the best result. This will also help us to determine the values that particular stock will have in near future.
We will determine the patterns in data with help of data mining algorithms.
The software will be developed using Asp .Net and will be cross checked and verified using “DB MINER” which is standard data mining tool.
An extension to the project that sends an sms to the user that is triggered on certain events can be added as an optional feature. 

3. Scope of the project

3.1 Application of Analysis of stocks in our selected domain:
Stock Market Analysis of stocks using data mining will be useful for new investors to invest in stock market based on the various factors considered by the software.
Stock market includes daily activities like Sensex calculation, exchange of shares. The exchange provides an efficient and transparent market for trading in equity, debt instruments and derivatives.
Our software will be analyzing Sensex based on company’s stock value. The stock values of company depend on some of the following factors:
1> Dollar value: The fluctuations in the dollar value day by day will be playing crucial part in the stock values of companies (basically I.T based companies) The impact of dollar values will be different for different companies.
2> Corporate results: This will be regarding to the profits or progress of the company over a span of time say 3 months.
3> Inflation: The overall rise in price of all the products which affects purchasing power.
The stock value depends on other factors as well, but we are taking into consideration only these particular factors.

3.2 Prominent features of the Project:
A. Analyzing stock data. 
We have obtained stock data of some companies that affect the Sensex. The data is from 2nd January 2006 to September 2007.The data has date as well as the value of the company’s stock at the end of trading session of that date.
B. Analyzing the factors.
     	We have to obtain the data in the same period for the following factors.
1. Dollar value: We will obtain the variation of dollar value as compared to the rupee.
2. Corporate results: Companies declare their performance results and profit at the end of each quarter.
3. Inflation: From financial experts we can obtain inflation rate over a period of time. 

We have to analyze the variations in the stock value of the companies with respect to these factors using some data mining algorithms. We will also verify our results with the results obtained by “DB miner” software.

SYSTEM REQUIREMENTS


     Functional Requirements

1. User Interface:  The user is required to select which company is he interested in amongst the various companies that have been provided. 
2. Visual Studio 2010 to Stock Database connectivity:  As communication with user is performed in C#.net and data required for processing is in a Database, a connectivity has to be implemented between the Database and Asp .Net application
3. Database to DB miner connectivity:  Pattern Analysis on the data in the database has to be performed using various mining tools provided by Db miner. Hence a connectivity between the two is required.

Advantages:

Helps the users in detecting the market trend patterns and other conditions.
The project report contains a number of filter elements ranging as per the market trends that helps the users to analyze the registered stocks
The project report contains a number of shares, their prices and Volume Breakouts
It contains stocks that have an unanticipated rise in the business volume and a rapid rate escalation in terms of cost.

Disadvantages:

Requires an active internet connection.
May generate inaccurate results if data inputted incorrectly.
