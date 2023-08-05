import pandas as pd
import yfinance as yf
from bs4 import BeautifulSoup
import requests

tsla=yf.Ticker("TSLA")
tesla_data=tsla.history(period="max")
tesla_data.reset_index(inplace=True)
print(tesla_data.head())
# print(tesla_data)