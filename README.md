# 📱 Playstore Review Analysis

Analyze and visualize user reviews from Google Play Store apps to uncover sentiment trends, user feedback themes, and app performance insights.

---

## 📌 Project Overview

This project focuses on extracting meaningful insights from Google Play Store app reviews using Natural Language Processing (NLP) techniques. It includes sentiment analysis, rating distribution, and topic modeling to understand what users love or hate about an app.

---

## 📂 Dataset Fields

| Column     | Description                                 |
|------------|---------------------------------------------|
| `reviewId` | Unique identifier for each review           |
| `content`  | Text of the review                          |
| `score`    | Numerical rating (1 to 5)                   |
| `app`      | Name or ID of the app being reviewed        |

---

## 🚀 Features

- 🔍 Sentiment analysis using VADER and machine learning models
- 📊 Visual analytics dashboard (Streamlit/Dash)
- ☁️ Word clouds for positive and negative reviews
- 📈 Rating distribution by app
- 🧠 Topic modeling with LDA to extract common feedback themes
- 📌 Filter reviews by app, rating, or sentiment


## 🏆 Top 20 Apps Analyzed
The following globally recognized and high-download apps are included in this analysis:

📘 Facebook

💬 WhatsApp

📩 Facebook Messenger

📸 Instagram

🎵 TikTok

🏃 Subway Surfers

🧊 Facebook Lite

📄 Microsoft Word

📊 Microsoft PowerPoint

👻 Snapchat

🔁 SHAREit

🎬 Netflix

🐦 Twitter

📰 Flipboard

🍬 Candy Crush Saga

🎥 Skype

🎧 Spotify

☁️ Dropbox

📞 Viber

📲 LINE



## 🧰 Tech Stack

- **Languages**: Python 3.x
- **Libraries**:
  - Pandas, NumPy
  - NLTK, SpaCy
  - VADER Sentiment
  - Scikit-learn
  - Gensim (for LDA)
  - Matplotlib, Seaborn, Plotly
  - Streamlit / Dash (for dashboard)


## 📊 Sample Visuals

- Rating distribution histogram
- Sentiment pie chart (Positive, Neutral, Negative)
- Word clouds of most frequent terms
- Topic modeling bar chart by app

## 📁 Folder Structure
```
playstore_review_analysis/
│
├── 01_data_collection/
│   └── raw_reviews.csv  # Contains the reviewId, content, score, app
│
├── 02_data_preprocessing/
│   └── clean_reviews.ipynb  # Text cleaning, null handling
│
├── 03_eda_visualization/
│   └── eda.ipynb  # Word clouds, rating distribution, etc.
│
├── 04_sentiment_analysis/
│   ├── vader_sentiment.py
│   └── sentiment_model.ipynb  # ML/NLP-based sentiment prediction
│
├── 05_topic_modeling/
│   └── topic_modeling_lda.ipynb  # LDA/NMF to extract common themes
│
├── 06_dashboard/
│   ├── app.py  # Streamlit / Dash dashboard
│   └── visuals/
│       ├── score_distribution.png
│       └── sentiment_pie_chart.png
│
├── data/
│   └── processed_reviews.csv
│
├── requirements.txt
└── README.md
```

## Install dependencies:
```
pip install -r requirements.txt
```
