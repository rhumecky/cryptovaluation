## Crypto Valuation Analysis

You can download the Jypyter Notebook for this project from:  

https://drive.google.com/drive/folders/1zd2FUV0GBfvzkU4lVUAL7LAEwgNuzGna?usp=sharing

The .csv of crypto data for modeling and predictions is available at:

https://drive.google.com/file/d/15GVKi5NAqel6-gJk8s4Uet4-pZ5lOVMw/view?usp=sharing



### Overview

Much of crypto price action in short term seems to be driven by momentum or sentiment, but longer-term pricing is driven by measurable fundamentals on adoption and usage.   This underlying data could be collected and used to quantitively value these cryptos and reveal mispriced assets.  This may yield nice short term trading opportunities.

### Challenges
This project requires collecting key performance and adoption data (10-30 data points per crypto) on at least 10 of the top 20 crypto smart contract platforms (subject to data availability).  Data collection needs to be automated using r, python or other tools to scrape data in near real time to provide timely information.   Collecting data will be a significant challenge because it will require gatering data from numerous sources.  

I tried using python data scraping tools like beautifulsoup to automate data collection and preparation.  However the sources I need to scrape were build to be resistant to web scrapers.  The actual data elements are buried in layers of java scripts that don’t render in python.  

I ended up having to  to collect the data manually from many sources including new articles for each block chain.  I also used a trial paid subscription to Messari to collect some data points.   

###Data Sources Used:
https://coinmarketcap.com/historical/
https://messari.io/screener/staking-stats-12A9F4C9  (Requires Paid Subscription)
https://messari.io/screener/chains-activity-DB01F96B  (Requires Paid Subscription)
https://defillama.com/chains
https://forkast.news/what-are-ethereum-killers-prospects-with-eth2/
https://alephzero.org/blog/what-is-the-fastest-blockchain-and-why-analysis-of-43-blockchains/
https://coinsutra.com/terra-network-luna-token-analysis/
https://www.investing.com/news/cryptocurrency-news/harmony-one-slow-and-steady-wins-the-race-2609585
https://www.investing.com/news/cryptocurrency-news/harmony-one-slow-and-steady-wins-the-race-2609585
https://aithority.com/technology/blockchain/btcs-adds-kusama-to-its-blockchain-infrastructure-operations/
https://blog.polygon.technology/what-do-you-prefer-maximum-security-or-cheaper-transactions/
https://blog.seedly.sg/zilliqa-singapore-guide/
https://neospcc.medium.com/10k-tps-on-neo-and-beyond-6790ac587dd4
https://www.banklesstimes.com/news/2021/12/22/near-price-forecast-likely-scenario-for-the-near-protocol/

