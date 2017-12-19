# Title
How do you feel about Trump's tweets?

# Abstract
This project relates to Donald Trump's tweets, more particularly the topics addressed by Donald Trump in his tweets, and the reactions of Twitter users to Donald Trump. We extract topics from Trump's tweets, and look at trends in these topics over the different years. We also assess the popularity of these topics among Twitter users based on the number of likes and retweets of the tweets, and based on sentiment analysis on replies to Donald Trump's tweets.

# Research questions
- How did topics addressed by Trump evolve with respect to time? 
- Is there a pattern for addressing a certain topic before or after the elections?
- What are the reactions of people to Trump's tweets?
- How do sentiments of people towards Trump differ with respect to different topics approached by Trump?

# Datasets
The chosen dataset is the one present at http://www.trumptwitterarchive.com/. It contains the following fields : source, text, created_at, retweet_count, favorite_count, is_retweet, id_str.
The data size of this dataset should be manageable since we do not have too many features to look at, and since the number of tweets by Trump is around 33,000.
We will also make use of the Twitter dataset, which is available on the cluster. The size of this data is very large (around 2.5 TB), and cannot be downloaded locally. Therefore, we run scripts on the cluster to extract the data relevant to our project from the Twitter dump (i.e tweets where Donald Trump is tagged).

# Group members roles
Fayez Mourad: problem formulation, text cleaning, experimenting with topic extraction methods, analysis of results, report
Yamane El Zein:problem formulation, sentiment analysis, data wrangling, analysis of results, visualization, report
