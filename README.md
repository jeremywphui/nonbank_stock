# nonbank_stock
Predict Nonbank Stock Prices

Project summary: Predict stock prices of publicly traded non-bank mortgage lenders using Fannie Mae loan level data and pricing data of the underlying stocks.

Background: Non-bank mortgage lenders have been growing in the past few years and starting to dominate the US mortgage market. Before 2019, the increase in borrowing costs caused by central bank's hawkish monetary policy slumped refinance business of mortgage lenders, the fact of which led banks to scale down their mortgage business. Since the beginning of 2019, central bank's monetary policy gradually turned from hawkish tone back to dovish tone (the monetary policy remains dovish from the GFC to 2017). Refinancing has grown again and mortgage lenders turned profitable because of the new 'Quantitative Easing' across the globe. Thus, it is interesting to see how the stock prices of non-bank mortgage lenders have been affected by the changing of economic regime during all these years.

Research Method: The research is a bottom-up style research, because it is based on loan level data.

Researches that used Fannie Mae loan level data: The Fannie Mae data has been available to public for many years and the data has been explored for multiple research purposes. The majority of the usage of the data is in risk management field, such as building risk metrics and building default prediction models. The difference between this proposed research and the majority of the publicly available researches is that this proposed research aims to predict stock price of non-bank lenders, rather than to predict default risk of given loans.

Model candidates: Linear Regression, Ridge Regression, Support Vector Regression, and ARIMA.

Potential Regressors: loan acquisition numbers, loan acquisition size, default rates, market coverage (by zipcode data), non-bank performance momentum, bank performance momentum, S&P 500 sector momentum, and interest rate move.

Application: Predict stock prices of non-bank lenders in the next 3-month, 6-month, and 1-year.
