# TwitterScraping
Twitter Scraping web app is created by using streamlit library in python.The main objective of Creating this web app is to scrape the hashtag tweets from the twitter and storing it in a database and also the tweets are downloaded in the form of json and csv format
#Required Tools
Language:python,Libraries:pandas,pymongo,snscrape,streamlit,Database:MongoDB
#Snscrape
To scrap the data Snscrape python library is used. The TweetSearchScrape() method scrape the Twitter data without Twitter API.
#Uploading Data into DB
The scraped data are inserted into the MongoDB database by establishing the clinet connection. The tweets are strored under the twitter db collections.
#Downloading as CSV and JSON files
The scraped data from the MongoDB database is downloaded as CSV/ JSON file formats

