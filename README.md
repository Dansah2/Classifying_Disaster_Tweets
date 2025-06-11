# 🌪️ Disaster Tweet Classification: NLP with Twitter Data

In times of natural disasters and emergencies, social media platforms like **Twitter** (now **X**) serve as powerful real-time communication tools. However, not every dramatic post indicates a real emergency. This project uses Natural Language Processing (NLP) to build a model that distinguishes between **real disaster-related tweets** and **non-disaster tweets**.

## 🎯 Project Objective

Using a dataset of **10,000 hand-labeled tweets**, our goal is to classify whether a tweet is **about a real disaster (Class 1)** or **not (Class 0)**.

We explore and compare the performance of **three different NLP techniques**:
1. **VADER (Valence Aware Dictionary for Sentiment Reasoning)**
2. **Bag of Words with traditional classifiers**
3. **Hugging Face Transformers (BERT-based model)**


## 🧾 Dataset Overview

- **Source**: [Figure Eight Disaster Tweets Dataset](https://www.kaggle.com/datasets/nlp-course/disaster-tweets)
- **Total Tweets**: 10,000
- **Features**:
  - `text`: The tweet content.
  - 'keywords': The key words in the tweet
  - 'location': The location the tweet was sent from
  - `target`: 1 = real disaster, 0 = not a disaster.
