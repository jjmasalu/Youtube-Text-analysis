
---

# YouTube Comments Analysis Project

## Project Overview

This project focuses on analyzing YouTube comments to extract valuable insights. The analysis includes data cleaning, sentiment analysis, word cloud generation, emoji analysis, and evaluating audience engagement. By leveraging various data analysis techniques, I aim to uncover patterns and trends in user behavior and preferences.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Data Extraction](#data-extraction)
3. [Data Cleaning](#data-cleaning)
4. [Sentiment Analysis](#sentiment-analysis)
5. [Word Cloud Analysis](#word-cloud-analysis)
6. [Emoji Analysis](#emoji-analysis)
7. [Category Analysis](#category-analysis)
8. [Audience Engagement](#audience-engagement)
9. [Conclusion](#conclusion)
10. [Dependencies](#dependencies)

## Data Extraction

The data for this project was extracted from YouTube videos. It includes comments, likes, dislikes, and view counts for each video. The data extraction process involved using YouTube’s API to gather information and store it in a structured format for further analysis.

## Data Cleaning

Data cleaning is a crucial step to ensure the accuracy and reliability of the analysis. The following tasks were performed:

- Removal of duplicates
- Handling missing values
- Filtering out irrelevant data (e.g., spam comments)

## Sentiment Analysis

Sentiment analysis was performed on the comments to determine the overall sentiment (positive, negative, or neutral) expressed by users. This was achieved using python libraries such as TextBlob.

## Word Cloud Analysis

A word cloud was generated to visualize the most frequently used words in the comments. This helps to identify common topics and themes discussed by users. The analysis involved:

- Removing stop words
- Generating the word cloud visualization

## Emoji Analysis

Emoji analysis was conducted to identify the most commonly used emojis in the comments section. This provides insights into the emotions and reactions of the audience. The steps included:

- Extracting emojis from comments
- Counting the frequency of each emoji
- Visualizing the most used emojis

## Category Analysis

The analysis also examined which video category received the maximum likes. This was done by aggregating the like counts for each category and identifying the category with the highest total likes.

## Audience Engagement

To understand audience engagement, I compared the number of views with likes, dislikes, and comments. This analysis helps to gauge how actively viewers are interacting with the content. Metrics calculated included:

- Like-to-view rate
- Dislike-to-view rate
- Comment-to-view rate
- Correlation among them

## Conclusion

The YouTube Comments Analysis Project provided valuable insights into user sentiment, popular topics, emoji usage, and audience engagement. The findings can help content creators and marketers better understand their audience and tailor their strategies accordingly.

## Dependencies

The project relies on the following Python libraries:

- pandas
- numpy
- TextBlob
- matplotlib
- seaborn
- wordcloud
- emoji
- plotly

To install the required dependencies, run:
```bash
pip install pandas numpy nltk textblob vaderSentiment matplotlib seaborn wordcloud emoji plotly
```

## Usage

1. Clone the repository
2. Extract YouTube data using the provided scripts
3. Run the data cleaning process
4. Perform sentiment analysis, word cloud analysis, emoji analysis, category analysis, and audience engagement analysis
5. Visualize the results

---
