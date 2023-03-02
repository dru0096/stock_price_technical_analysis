# stock-price-technical-analysis :chart:

## Objective: help a user make better buy/sell decisions and increase returns on short-term investments.

## Background
This is my Ironhack bootcamp project. The idea initiated when I was asked by an early-stage company to transform excel logic into python logic to identify specific stock price patterns. I create a workflow that can run daily and email alert the user on the same day the pattern is formed. 

## Steps: 
* Clean the dataset
* Build interactive dashboards to explore the data over time
* Apply the statistical techniques (Shapiro Wilk and two sample tests) to derive conclusions

## Technical skills used
* Python
* HTML - for streamlit application
* API connections
* Email Automation tools
* Statistical Tests - T-test


## Data source
Food Companies on Bombay Stock Exchange available with Nasdaq API 
Note: it is possible to replace this with CSV data that is updated on a daily basis

## Repository Folders/Contents
1. Streamlit App > Data - contains the data used to perform t-tests to evaluate returns during a buy/sell action, X (5, 14, 28) number of days a pattern is identified.
2. Streamlit App > Notebooks - contains the notebooks to code the python pattern inspector functions, candlestick plots, and draft workflow for interface.
3. Streamlit App > Functions - compilation of importable functions
4. Streamlit App > Plotly_Candlestick_Charts  - a folder where charts will save for email alert attachment
5. Streamlit App > st_pickles - used only in ``` dashboard.py ``` for streamlit interface
