# Covid-19: Data Collection and Exploration from Twitter - Sentiment analysis

In this project I create an app to stream live tweets from Twitter on the subject of Covid-19.

## Create a twitter app
I collect 50000 tweets and perform and an exploratory data analysis on the data.

## Exploratory data analysis

I explore the data as following:
* number of unique users
* number of unique locations
* number of unique users mentioned within the tweets
* plot distribution of languages
* plot numbre of tweets per minute
* find top 3 most frequently used locations

### Filtering - Sentiment analysis

I assume that simple emoticons can capture the sentiment of a tweet. This emoticons can be coded using regular expressions. Based on that I calculate the number of tweet that have positive and negative sentiment.

### Text pre-processing

Finally I clean the data by using regular expressions to extract:

* Punctuation
* Digits
* New line characters
* URL links
* References to users: @user
* Hashtags
