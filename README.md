# Stock-price-and-news-alert
This is an app for tracking the price of a stock during the last two days and sending e-mail with the relevant news if the price moves more than 5%. The price is tracked using an API request from the website https://www.alphavantage.co/, while the news are extracted from the website https://newsapi.org/ again using an API request. THe e-mail is sent using the smtplib library of Python. The user has to provide his/hers e-mai, app password and the keys for the APIs.  