# PRODIGY_DS_04
This Python script is designed to analyze and visualize sentiment patterns in social media data, particularly from Twitter. The analysis aims to provide insights into public opinion and attitudes towards various topics or brands, which can be instrumental for market research, political campaigns, and public relations.

Data Source:
The sentiment analysis is performed using two datasets:

- twitter_training.csv: Contains training data for the model, including tweet IDs, topics, sentiments, and the tweet text.
- twitter_validation.csv: Contains validation data similar in structure to the training data.

Usage:
Data Preparation:
- Load the training and validation datasets.
- Understand the basic structure of the data through its first few rows.
  
Data Cleaning:
- Implement a function to clean the tweets by removing URLs, mentions, special characters, and converting text to lowercase.
  
Sentiment Analysis Across Different Topics:
- Combine the training and validation datasets for a holistic analysis.
- Group and count sentiments per topic, and visualize the distribution using a bar plot.
  
Overall Sentiment Distribution:
- Visualize the overall sentiment distribution to understand the general sentiment bias in the tweets.
  
Word Frequency Analysis:
- Analyze the frequency of words in positive tweets using a word cloud to identify common terms and gauge the context behind positive sentiments.

Visualization Details:
The script employs bar plots and word clouds to present the data:
- Bar plots are used to show the sentiment distribution across different topics and the overall sentiment distribution.
- Word clouds are used to visualize common terms in positive tweets, highlighting key themes or concerns associated with positive sentiments.
