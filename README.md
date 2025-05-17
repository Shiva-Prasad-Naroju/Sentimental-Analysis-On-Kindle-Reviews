# 📚 Amazon Kindle Review Sentiment Analysis 🔍

This project dives into a subset of the Amazon product reviews dataset (Kindle category) to analyze customer sentiment using multiple text vectorization techniques.

## 🧠 Project Objective:

- Understand the sentiment behind product reviews 🗣️

- Classify the star rating (1–5) based on the review content ⭐

- Explore the impact of different feature extraction techniques on classification performance 📊

## 🛠️ Techniques Used:

We experimented with 3 popular Natural Language Processing (NLP) approaches:

- Bag of Words (BoW) 👜

- TF-IDF (Term Frequency – Inverse Document Frequency) 📈

- Word2Vec Embeddings 🧬

## 📦 Dataset Overview:

- Source: Amazon Kindle Store Reviews (5-core version)

- Entries: 982,619 reviews

- Time Span: May 1996 – July 2014

## Features Used:

textReview 📝 — Actual review text

rating ⭐ — Review rating (1 to 5)

## 🧪 Model Used:

Gaussian Naive Bayes (GNB) 🧮 — Chosen for its simplicity and effectiveness in text classification tasks.

## 📊 Evaluation Metrics:

Each model's performance was evaluated using:

- Accuracy

- Confusion Matrix

- Classification Report (Precision, Recall, F1-Score)

## ✅ Results Summary:

Technique	Accuracy (%)
BoW	      58%
TF-IDF	  57%
Word2Vec	57%

## 🧠 Takeaway:
This project served as a strong foundation in learning how to apply text vectorization methods and build classification models. While the results weren’t high, they highlight the challenges in real-world sentiment analysis and the need for more advanced models (like deep learning, transformers, or context-aware embeddings).

## 🚀 Let's Connect:

If you found this useful or want to collaborate, feel free to reach out!
🧑‍💻 Happy Learning!
