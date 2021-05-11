# Web-Scraping-for-Gender-Based-Violence
To create a dataset that can be used for research, data analysis, and model training concerning the matter of Gender Based Violence.
The code attached to this repo teaches us how to scrape data from twitter for sentiment analysis .
The data will have to be cleaned before being used for analysis or trained with a model.

The data containd the following columns:


Tweets: Shows the opinions posted by twitter users concerning the issue of gender based violence.
	Some of these tweets are orginal opinions generated by the user themselves, while others are retweets. 
	All under the hashtag 'Gender Based Violence'.
	Every tweet contains both the opinion of the user alongside, the users handle. The users handle is a means
	of identifying the user.

id: All tweets scraped have an identity number. Therefore, 'id' shows the identity number of each tweet.

lens: The number of characters per tweet.

date: The date and time the tweets were tweeted.

place: The location of the twitter user that tweeted.

coordinates: The coordinates of the users location.

language: The language in which the tweet was written in by the user. For enxample 'en' = English.

source: It shows the device/gadget used by the twitter user to tweet. 'Twitter for Android' means the user used an 
	Android device to tweet. 'Twitter for iPhone' means the user specifically used an Apple device called an iPhone
	to tweet.'Twitter Web App' means the user used a web browser on their phone or laptop to tweet.

likes: It shows the number of Twitter users that liked the tweet by clicking on the like emoji on Twitter.

Retweet: It shows the number of times the tweet was tweeted verbatim by other Twitter users.

