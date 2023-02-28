# TwitterScraping
Twitter Scraping web app is created by using streamlit library in python.The main objective of Creating this web app is to scrape the hashtag tweets from the twitter and storing it in a database and also the tweets are downloaded in the form of json and csv format
## Required Tools
**Language**:python,**Libraries**:pandas,pymongo,snscrape,streamlit,**Database**:MongoDB
## Scraping the tweet
**Snscrape** library in python is used to scrape the tweets from the twitter.The **TweetSearchScrape()** method scrape the Twitter data without Twitter API.
## Uploading Data in MongoDB
The scraped tweets are inserted into the MongoDB database by establishing the clinet connection. The tweet datas are strored under the twitter db collections.
## Display the data
The scraped data from the MongoDB database are dispalyed as a DataFrame
## Download as CSV/JSON format
The scraped data from the MongoDB database is downloaded as CSV/ JSON file formats


