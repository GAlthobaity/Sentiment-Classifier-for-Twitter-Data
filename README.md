# Sentiment-Classifier-for-Twitter-Data
*This project is a part of the ["Python Functions, Files, and Dictionaries"](https://coursera.org/share/9cceb06e8ef852aa6a4a6a58c870f4db) course offered by the University of Michigan via Coursera.*

This project focuses on building a sentiment classifier for Twitter data. The goal is to analyze the sentiment of each tweet by detecting positive and negative words and calculating scores based on the number of occurrences. The resulting data is then stored in a CSV file, and a graph is generated to visualize the relationship between the net score and the number of retweets.

## Description
In this project, we provide synthetic Twitter data in a CSV file (project_twitter_data.csv), which includes the text of a tweet, the number of retweets, and the number of replies. Additionally, we have two text files (positive_words.txt and negative_words.txt) containing positive and negative sentiment words.

**The main tasks of this project are as follows:**
* Develop a function called strip_punctuation to remove punctuation characters from a word.
* Create get_pos function to calculate the number of positive words in a given sentence or set of sentences.
* Create get_neg function to calculate the number of negative words in a given sentence or set of sentences.
* Build a sentiment classifier by loading project_twitter_data.csv file and analyzing each tweet's sentiment.
* Generate a CSV file named resulting_data.csv that contains the Number of Retweets, Number of Replies, Positive Score, Negative Score, and Net Score for each tweet.
* Create a graph of the Net Score vs Number of Retweets.

## Net Score vs Number of Retweets Graph
* There is no clear linear relationship between the Net Score and the Number of Retweets. The Net Score does not consistently increase or decrease with the Number of Retweets.
* Tweets with a higher number of retweets generally have positive or neutral Net Scores.
* Some tweets with a low number of retweets have relatively high Net Scores, indicating positive sentiment despite less engagement.
* There are instances where tweets with zero or minimal retweets have negative Net Scores, indicating negative sentiment despite low engagement.

![image](https://github.com/GAlthobaity/Sentiment-Classifier-for-Twitter-Data/assets/60229547/028dfcd6-a5ea-46b1-96ac-012601b05727)
