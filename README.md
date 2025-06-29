# 📊 Reddit Sentiment Analysis

Analyze public sentiment about any brand or topic using Reddit data. This project fetches Reddit posts, cleans the text, applies sentiment analysis, and visualizes the results with charts and word clouds. It's fully compatible with **Google Colab**.

---

## 🔍 Overview

This project allows users to:
- Enter a brand/topic (like "Zomato", "Swiggy", or "OnePlus")
- Automatically fetch the latest Reddit posts about it
- Clean the text data
- Analyze sentiment using VADER (Valence Aware Dictionary)
- Show results through graphs and word clouds

---

## ⚙️ Features

- 🔄 Reddit scraping using `praw`
- ✨ Sentiment analysis with `vaderSentiment`
- 🧹 Text preprocessing using `nltk`
- 🎨 Word cloud generation for positive/negative posts
- 💬 Input brand/topic directly in code (Colab-friendly)

---

## ▶️ How to Run (Google Colab)

> ✅ [Open this notebook in Colab](https://colab.research.google.com/drive/YOUR_NOTEBOOK_ID) *(replace with actual link)*

1. Run all cells step by step
2. Enter your Reddit API credentials (free to get)
3. Change the `brand = "Zomato"` variable to your desired topic
4. View sentiment distribution and word cloud

---

## 🔧 Requirements

Install these libraries in Colab or your local environment:

```bash
praw
pandas
matplotlib
seaborn
vaderSentiment
wordcloud
nltk
ipywidgets
```

---

## 📁 Folder Structure

```
Reddit-Sentiment-Analysis/
├── Reddit_Sentiment_Analysis.ipynb   ← Main Colab Notebook
├── README.md                          ← Project Documentation
└── requirements.txt                   ← Python dependencies
```

---

## 📝 Reddit API Access

1. Go to [https://www.reddit.com/prefs/apps](https://www.reddit.com/prefs/apps)
2. Create an “Installed App” to get:
   - `client_id`
   - `client_secret`
   - `user_agent`
3. Paste them in the Colab notebook to start fetching Reddit posts

---

## 📊 Sample Output

- Sentiment distribution (Positive / Negative / Neutral)
- Word clouds for top words in positive and negative posts
- Raw post + sentiment label preview

---

## 👨‍💻 Author

**Aditya Pal**  
🔗 [GitHub: Aditya-Pal01](https://github.com/Aditya-Pal01)

---

## 📜 License

MIT License – Free for academic, personal, and open-source use.

---

## 📌 Notes

- This project does not store or misuse Reddit data
- Ideal for NLP, sentiment analysis, and data visualization practice
