# Uber-Price-Forecasting
Webscrapes for exact fare estimates on Uber website. Uses LSTM and Prophet model for time series prediction for future Uber fare prices.

UBER WEBSCRAPING AND TIME SERIES PREDICTION
First, scrapes for fare data on Uber estimate website using Selenium - Then charts it and gather this data in a csv file - After cloning, do create a csv file to hold data scraped from website

Second, trained several(hope to be several) time series prediction models including LSTM and Facebook Prophet to identify key trends and is capable of predicting future fare estimates.

TO USE WEBSCRAPER:
Clone project
Import from requirements.txt
Add data.csv to webscraper directory
Run main_Webscraper once, and in that automated window, create a Chrome profile of the email that you are using to scrape data off of Uber.
Primary issue was that to get a proper fare estimate, Uber requires you to login, hence the Chrome profile.
From then on, it should run smoothly
