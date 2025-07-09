# Analyzing-Twitter-Tweets

## 📌 Project Overview
A sentiment and engagement analysis of airline-related tweets using real-world Twitter data. 
The project explores customer sentiment trends across airlines and engagement patterns through visualizations and statistical summaries.

**📊Data Cleaning & Preparation**
Converted the tweet_created field to datetime format.
Dropped missing and irrelevant fields to maintain data quality.
Selected key columns such as airline, airline_sentiment, retweet_count, and text, date

**📈 EDA: Sentiment Distribution**
Explored retweet patterns as a proxy for user engagement.
Created time series plots to observe trends in tweet volumes.
Performed sentiment-wise statistics to compare average retweets and tweet volumes.

## 📌 Conclusion & Key Takeaways
Negative tweets dominate most airline mentions, with airlines like United and American receiving higher negative sentiment.
Engagement (retweets) does not vary significantly by sentiment on average, but outliers exist, where strongly worded tweets are shared more.
Tweet volume patterns suggest that social media activity spikes around certain periods, possibly in response to delays or service failures.
