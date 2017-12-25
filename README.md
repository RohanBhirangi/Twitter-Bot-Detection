# Detection of Twitter Bots using Machine Learning Classifiers

## Introduction
Twitter is the most popular social networking and microblogging website. Twitter users share messages and other multimedia using tweets and direct messages. Twitter is filled with millions of automated bot users who are programmed to generate large amount of tweets delivering news and updates. However, many bots are also used to spread spam, malicious content and propagate false news. We have collected the twitter data of 2797 twitter accounts, some of which are bots. This data includes several attributes related to the twitter account like name, characteristics, etc. The data is to be analyzed based on those attributes to correctly identify whether a twitter user is a bot or not. The proposed classification system uses variations of 3 major classifiers viz., Decision Tree, Logistic Regression and Naïve Bayes classifiers. The various attributes of the twitter user can be used to predict whether the user is a human or a bot.

## Observations
* Decision Tree classifier provides the highest accuracy
* High precision (>97%) values for all the classifiers
* High precision denotes low false-positives (the probability of a user being identified as bot when it is a non-bot is low)
* Thus, the models efficiently identify a non-bot account
* But we get low recall score for the classifiers
* Which means there are a lot of false-negatives in our prediction
* These are twitter accounts which are bots but are identified as non-bots