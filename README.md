# onepanel
## Portfolio management using horoscopes
Fairly straightforward, just run through the notebook horoscope+allocations.ipynb. If the scraping crashes the notebook, just refresh it and restart whatever block failed. Cell 10 is where the stocks are defined. If you want to swap out for different tickers, there are plenty to choose from.

## Predicting stock performance based on CEO pictures
### Step 1:
Run CEO+stock+scraping.ipynb to get the stock performances we'll be predicting. You'll want a free Quandl account to be running this, or you'll be capped at 50 queries per day.
### Step 2:
Run scraper/CEO image scraping.ipynb to scrape all the photos of the CEOs.
### Step 3:
Run CEO+training.ipynb to train the model for predicting performance based on CEO photos.
