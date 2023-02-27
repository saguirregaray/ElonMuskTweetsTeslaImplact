# ElonMuskTweetsTeslaImplact
Elon Musk's Tweets impact over Tesla's Stock

## Project description

This repository contains the code for a study performed on Elon Musk’s tweets and Tesla stock price using various statistical methods. 

The dataset used was a merged dataset containing the tweets, sentiment and stock price of Tesla. New variables were introduced like if the tweet was professional or not, if the stock price went up or no, and a general delta stating the net change in closing price of Tesla stock. 

The tweets were preprocessed by various techniques using NLTK and Regular Expressions and were then passed into the RoBERTa base model to get the sentiments for each tweet. Then, an average daily senti- ment was used for a daily analysis on stock price. Chi-sq test of independence was performed on sentiments and increase in stock price variable and no relation between the sentiments and stock price was found. H-Test also yielded that there is no difference in the impact of different sentiment groups on the stock price. Whereas, with the Chi-Sq test it was found out that there is a relation between professional/non-professional tweet vari- able and increase in stock price variable. With the help of U-Test, it was also found out that there is statistical difference in the impact of a professional tweet and a non-professional tweet.
