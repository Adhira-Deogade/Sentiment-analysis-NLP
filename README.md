# Uncovering sentiments - EDGAR dataset

Sentiment analysis - Facebook call earnings Q4

## Data
Description: [Earnings call](https://www.investopedia.com/terms/e/earnings-call.asp) is a conference call between the management of a public company, analysts, investors, and the media to discuss the company’s financial results during a given reporting period, such as a quarter or a fiscal year. An earnings call is usually preceded by an earnings report. This contains summary information on financial performance for the period.

Sentiment analysis is particularly challenging in domains such as finance. Earnings call is a good example of set of sentiments which are difficult to interpret if they are leading in po
## Data collection:
1. Obtain the latest earnings call transcript Q4 2018 for Facebook
2. Get it from seekingalpha.com or EDGAR (sec.gov)
3. Scraped the website with BeautifulSoup package in python

```from bs4 import BeautifulSoup```
4. Fetch 

```from urllib.request import urlopen
from urllib.request import Request```

