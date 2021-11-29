# is-417-final-project


The hypothesis being tested is: Do the markets reflect rational behavior or human irrationality? 
Mass psychology's effects may not be the only factor driving the markets, but it’s unquestionably significant 

The effect of peoples opinion as expressed on Twitter is used to determine how the public emotion affects the stock market.
Sentiment analysis and machine learning principles will be used to find the correlation between ”public sentiment” and ”market sentiment”.
Time series model of public sentiment can be correlated to the time series pattern for the stock prices.

The hypthesis has ben tested on 3 major market brands known by all i.e. Apple, Tesla and Walmart.

The dataset used will be the tweets collected for a certain duration and the stock prices for the same duration for each individual company.
Twitter data is obtained using the sns.scrape library in python.
Stock price data is obtained from Yahoo Finance

Granger causality is based on linear regression, but the correlation between stocks and moods is certainly non linear. Granger causality can be used to map the correlation between the two obtained time series models.
