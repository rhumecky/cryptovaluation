## Crypto Valuation Analysis

You can download the Jypyter Notebook for this project from:  

https://drive.google.com/drive/folders/1zd2FUV0GBfvzkU4lVUAL7LAEwgNuzGna?usp=sharing


### Overview

Much of crypto price action in short term seems to be driven by momentum or sentiment, but longer-term pricing is driven by measurable fundamentals on adoption and usage.   This underlying data could be collected and used to quantitively value these cryptos and reveal mispriced assets.  This may yield nice short term trading opportunities.

### Challenges
This project requires collecting key performance and adoption data (10-30 data points per crypto) on at least 10 of the top 20 crypto smart contract platforms (subject to data availability).  Data collection needs to be automated using r, python or other tools to scrape data in near real time to provide timely information.   Collecting data will be a significant challenge because it will require gatering data from numerous sources.  

I tried using python data scraping tools like beautifulsoup to automate data collection and preparation.  However the sources I need to scrape were build to be resistant to web scrapers.  The actual data elements are buried in layers of java scripts that don’t render in python.  

Looks like I will have to collect the data manually for now to not hold up the critical parts of the project.  After modeling is complete and I know what elements are most valuable, I may try to automate some of those later.  Might require paid subscriptions to API sources. 
