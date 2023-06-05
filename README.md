# Twitter Text Analysis

This project aimed to analyze and gain insights from a sample of tweets of several high-profile public figures. By leveraging data science techniques such as source analysis, sentiment analysis, and time series analysis, I aimed to understand customer sentiments, identify trends over time, and analyze the sources of the reviews.

## Source Analysis
To understand the sources of the tweets, whether it was the from individual (e.g., from an iPhone) or a public relations firm (e.g., TweetDeck), I extracted HTML tags of the platform or website from which the tweet was published.

## Time Series Analysis
Analyzing the temporal aspect of the data was essential in identifying trends and understanding the evolution of tweet publication over time. A key step involved visualizing timestamp trends using a line and density plots, taking into account the respective timezones of each user and displaying the distribution of tweet posting hours. Examining the temporal aspect of the data uncovered valuable insights about user behavior throughout the day, including their eating and sleeping patterns.

## Sentiment Analysis
Using Natural Language Processing (NLP) techniques, I analyzed the sentiment of each tweet by calculating their polarity score. This approach allowed me to obtain a quantitative measure of how users perceive certain subjects and people. I used regular expressions and the *VADER (Valence Aware Dictionary and sEntiment Reasoner)* lexicon to preprocess the text, tokenize the reviews, and apply sentiment classification algorithms.

