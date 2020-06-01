# Finding-Cost-of-Living-using-Web-Scraping

### Numbeo Web-Scraper
This folder contains a web-scraper to scrape Numbeo for cost of living data. It will scrape all the data that Numbeo will allow you to for a given country and location (Numbeo fairly prevents scrapers, and so you won't get much if you try). It will give back all of the information that you could get for every location within a search query. The information is stored in a MongoDB database.

### Usage
This scraper is built to scape Numbeo for an inputted country and location. To use it, you can simply call it from the command line as follows:

  `python scrape.py`   for scrapping all cost of living information
