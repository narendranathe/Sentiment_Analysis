#Sentiment Analysis of Yelp & Trip Advisor Reviews

##Overview

This GitHub repository houses the project on conducting sentiment analysis on reviews collected from Yelp and Trip Advisor. The aim is to decipher the sentiment behind user reviews using advanced NLP techniques, thereby uncovering insights into public opinion about local businesses.

##Project Objective

The primary goal is to analyze and classify the sentiments of reviews into positive, negative, or neutral categories, providing stakeholders with a deeper understanding of customer feedback and its implications for business reputation and service quality.

##Technologies Used

- **Data Manipulation**: `pandas`, `numpy`
- **Text Processing & Sentiment Analysis**: `spacy`, `nltk`, `transformers`
- **Visualization**: `matplotlib`, `seaborn`, `wordcloud`
- **Machine Learning Models**: BERT, RoBERTa for sentiment classification.

##Workflow

1. **Data Collection**: Reviews were scraped from Yelp and Trip Advisor using custom scripts.
2. **Preprocessing**: Text data was cleaned and preprocessed to remove noise and standardize the format for analysis.
3. **Sentiment Analysis**: Applied NLP models to categorize reviews based on sentiment.
4. **Visualization and Analysis**: Visualized results using graphs and word clouds to identify trends and patterns in sentiment.
5. **Comparative Study**: Compared sentiments across Yelp and Trip Advisor to highlight platform-specific trends.

## Installation

Instructions for setting up the project environment:

```bash
git clone <https://github.com/narendranathe/Sentiment_Analysis>
cd <project-directory>
pip install -r requirements.txt
