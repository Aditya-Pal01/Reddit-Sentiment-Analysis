# 📊 Reddit Sentiment Analysis

Analyze the sentiment of Reddit posts about any brand or topic using Python, VADER, and visualizations.

---

## 🔍 Overview

This project uses the Reddit API (via PRAW) to fetch posts related to a brand or keyword, cleans the text, performs sentiment analysis using VADER, and displays results with count plots and word clouds. It's designed to run interactively in **Google Colab**.

---

## ⚙️ Features

- Reddit scraping using `praw`
- Text preprocessing with `nltk`
- Sentiment analysis with `vaderSentiment`
- WordCloud generation for positive and negative posts
- Interactive brand input using `ipywidgets`

---

## ▶️ How to Run in Google Colab

1. Open this notebook in Google Colab: *(Add link after upload)*
2. Run all cells step-by-step:
   - Install dependencies
   - Enter your Reddit API credentials
   - Enter a brand or topic to analyze (e.g. `"Swiggy"`, `"OnePlus"`)
   - View sentiment distribution and word clouds

---

## 🔧 Requirements

Install the following in Colab or locally:

```bash
praw
pandas
matplotlib
seaborn
vaderSentiment
wordcloud
nltk
ipywidgets

