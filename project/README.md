# Title
Reactions of people to Trump's tweets

# Abstract
We will be looking into Trump's tweets in order to identify the popularity of some problems addressed by Donald Trump among his followers. We will be looking into the number of likes, retweets and number of replies to assess popularity of a tweet, along with performing sentiment analysis on tweets that are replies to Trump from a Twitter dump. We will also try to identify trends among the topics addressed by Trump with respect to time (i.e. was the same topic addressed by Trump more often before or after the election?).
The motivation behind this project is to find the problems that need to be looked at more closely in the United States, based on people's opinions.

# Research questions
- How did topics addressed by Trump evolve with respect to time? 
- Is there a pattern for addressing a certain topic before or after the elections?
- What are the reactions of people to Trump's tweets?

# Datasets
The chosen dataset is the one present at http://www.trumptwitterarchive.com/. It contains the following fields : source, text, created_at, retweet_count, favorite_count, is_retweet, id_str.
The data size of this dataset should be manageable since we do not have too many features to look at, and since the number of tweets by Trump is around 33,000.
We will also make use of the Twitter dataset, which is available on the cluster. The size of this data is very large (around 2.5 TB), and cannot be downloaded locally. Therefore, we will need to run scripts on the cluster to extract the data relevant to our project from the Twitter dump (i.e tweets where Donald Trump is tagged).

# A list of internal milestones up until project milestone 3
- Choose the best method of topic identification from Trump's tweets and tune it to get relevant results.
- Fetch relevant data from the cluster
- Perform sentiment analysis on the relevant data to assess people's reactions to Trump
- See how people's reacctions evolve with respect to time and with respect to the topics mentioned in Trump's tweets.
- Report
