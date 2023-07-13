# Youtube Comment Analysis

This repository contains code for analyzing YouTube videos using the YouTube Data API. It retrieves video data, including information about the videos and their comments, and performs various analyses on the data.

- Established Youtube API for extracting comments for top 50 videos about The Matrix Resurrections Movie
- Simplified comments by text preprocessing and lemmatization
- Generated NLP analysis with word frequency table and WordCloud

## Prerequisites
Before running the code, you need to set up an API key. Follow these steps to obtain an API key:

1) Go to the Google Cloud Console.
2) Create a new project or select an existing project.
3) Enable the YouTube Data API v3 for your project.
4) Go to the Credentials page and create a new API key.
5) Copy the API key and replace the placeholder YOUR_API_KEY in the code with your actual API key.

## Usage
The code in this repository performs the following tasks:

1) Searches for YouTube videos related to "The Matrix Resurrections" using the YouTube Data API.
2) Retrieves details about the top 50 videos, including their titles, IDs, durations, views, likes, and comments.
3) Extracts the most relevant comment from the first video and displays it.
4) Processes and filters the comments to keep only English comments.
5) Performs text preprocessing on the comments, including tokenization, lowercasing, removal of punctuation, removal of stop words, and lemmatization.
6) Calculates the word count of each comment and plots a boxplot showing the distribution of word counts.
7) Identifies the top 20 most common words among all the comments and displays them with their frequencies.
8) Generates a word cloud visualization of the comments.
9) Please ensure that you have replaced the YOUR_API_KEY placeholder in the code with your actual API key before running it.

## Notes
- This code was last updated in September 2021. It uses the google-api-python-client library to interact with the YouTube Data API. Please refer to the official documentation for any changes or updates to the API.
- The code makes use of external libraries such as pandas, nltk, langdetect, matplotlib, seaborn, and wordcloud for data processing, analysis, and visualization. Make sure these libraries are installed before running the code.
- The code assumes that you have already set up the necessary authentication and have the required permissions to access the YouTube Data API.

## Most Frequent Words - Top 20
![](https://github.com/mustafagol/youtube_api/blob/025ee465a7c77ec20da3e5f5f2f82b665cd9dc85/WorldCloud.png)
