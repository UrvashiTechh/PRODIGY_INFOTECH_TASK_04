# PRODIGY_INFOTECH_TASK_04
TASK 4
💬 Social Media Sentiment Analysis – Public Opinion Mining
<img width="1680" alt="Screenshot 2025-07-04 at 11 22 24 AM" src="https://github.com/user-attachments/assets/fbcab8c1-ee43-4c94-9555-910ae4da49c2" />
📌 Overview
This project aims to analyze and visualize sentiment patterns in social media data to understand public opinions, emotions, and attitudes toward specific topics, brands, or events.

Using Natural Language Processing (NLP) techniques and visual analytics, I explored public sentiment using tweets/comments and categorized them as positive, neutral, or negative.

🎯 Objective
To perform sentiment analysis on social media text (e.g., Twitter data) and generate insightful visualizations that reveal:

The general sentiment trend around a topic or brand

Sentiment distribution over time or by keyword

Most common words and hashtags associated with each sentiment

📁 Dataset
The dataset used contains social media posts (e.g., tweets or YouTube comments) with the following columns:

text: the content of the post

timestamp: when it was posted

username: the account that posted

label or sentiment: sentiment score (if pre-labeled or predicted)

Sample source: Kaggle Twitter Sentiment Dataset or your scraped/collected dataset.

🛠️ Tools & Libraries
Python

Jupyter Notebook

pandas, numpy – data manipulation

matplotlib, seaborn, wordcloud – visualizations

nltk, TextBlob, VADER – sentiment analysis

(Optional: tweepy or snscrape for live data scraping)

🔍 Steps Performed
✅ Data Preprocessing
Cleaned text (removed URLs, mentions, special characters)

Tokenized, lemmatized, and removed stopwords

Handled missing and duplicate entries

🧠 Sentiment Analysis
Applied VADER and/or TextBlob for polarity scoring

Classified sentiments as: positive, negative, or neutral

📊 Visualization
Bar chart: sentiment distribution

Pie chart: proportion of each sentiment

Time series plot: sentiment trend over time

WordClouds: most frequent words in each sentiment category

📈 Sample Insights
The majority of users expressed positive sentiment about the brand

Negative spikes were linked to specific dates or product issues

Keywords like "love", "update", and "support" were dominant in positive comments

Words like "crash", "delay", and "hate" appeared in negative comments

🧪 Possible Extensions
Apply deep learning with BERT or RoBERTa

Perform topic modeling (e.g., LDA)

Analyze sentiment per country or region

Deploy via Streamlit or Flask as a dashboard
