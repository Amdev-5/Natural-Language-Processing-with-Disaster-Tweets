# Natural-Language-Processing-with-Disaster-Tweets

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

The Dataset has been taken from Kaggle. There are 2 dataset train.csv and test.csv.

Each sample in the train and test set has the following information:

The text of a tweet
A keyword from that tweet (although this may be blank!)
The location the tweet was sent from (may also be blank)


Columns
id - a unique identifier for each tweet
text - the text of the tweet
location - the location the tweet was sent from (may be blank)
keyword - a particular keyword from the tweet (may be blank)
target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)


Notebook includes Exploratory Data Analysis of Tweets, preprocessing like removing URLs, Removing HTMLs, Removing Emojis
Spelling Corrections Next apply lemmatization then text vectorization and then finally building a neural network to pclassify the tweets if it is disaster tweets or non-disaster tweets
