# Title
Main concerns among Trump followers

# Abstract
We will be looking into Trump's tweets in order to identify the popularity of some problems addressed by Donald Trump among his followers. We will be looking into the number of likes, retweets and number of replies to assess popularity of a tweet. We will also try to identify trends among the topics addressed by Trump with respect to time (i.e. was the same topic addressed by Trump more often before or after the election?). And finally, we will try to find if a topic becomes more popular as the number of tweets by Trump relating to it increases.
The motivation behind this project is to find the problems that need to be looked at more closely in the United States, based on people's opinions.

# Research questions
- How did topics addressed by Trump evolve with respect to time? 
- Is there a pattern for addressing a certain topic before or after the elections?
- What are the most important issues among Trump's followers?

# Dataset
The chosen dataset is the one present at http://www.trumptwitterarchive.com/. It contains the following fields : source, text, created_at, retweet_count, favorite_count, is_retweet, id_str.
We can also perform queries on the dataset based on specific search terms, which can help us aggregate tweets by topic. 
To find the number of replies on the tweets, we will use the Twitter Search API with the tweet id available in the dataset and Trump's username. 
The data size should be manageable since we do not have too many features to look at, and since the number of tweets by Trump is around 33,000.

# A list of internal milestones up until project milestone 2
- Nov 6th: Store all the data locally (feasible with the current size of the tweets). Preprocess the data by removing stop words, lower case, special characters etc.
- Nov 13th: Topic identification using different techniques present online such as tf-idf to identify the importance of a word which may include the topic. Use some third party libraries such as Fast Text to identify topics as well.
- Nov 21st: Plot visuals of different topics with respect to time.

# Questions for TAa
- 
