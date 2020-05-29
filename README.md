# Medium Blog

https://medium.com/@abhishek.palle123/multi-label-topic-classification-of-tweet-25c5eeef61a6

# Multi-Label-Topic-Classification-of-Tweet

• Extracted tweets from twitter for different combinations of topics - ['electronics'], ['politics'], ['travel'], ['car'], ['electronics','car'], ['politics','car'], ['travel','car'], ['politics','travel'], ['travel','electronics']

• Performed data pre-processing steps like tokenizing tweets, removing stop words, removing unwanted punctuations using regular expressions and creating features using tf-idf

• Used Ensemble of Classifier Chains to extract all the topics a user is talking about in a tweet

• Used precision score as a evaluation metric as the intention is make sure all the recommeded tweets are relevant to the user, so we want high precison

• On test data, achieved micro-average precision score of 97.105 & macro-average precision score of 97.173
