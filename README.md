# 📚 Amazon Kindle Review Sentiment Analysis 🔍

This project dives into a subset of the Amazon product reviews dataset (Kindle category) to analyze customer sentiment using multiple text vectorization techniques.

## 🧠 Project Objective:

- Understand the sentiment behind product reviews 🗣️

- Explore the impact of different feature extraction techniques on classification performance 📊

## 🛠️ Techniques Used:

We experimented with 3 popular Natural Language Processing (NLP) approaches:

- Bag of Words (BoW) 👜

- TF-IDF (Term Frequency – Inverse Document Frequency) 📈

- Word2Vec Embeddings 🧬

I implemented several essential text preprocessing techniques including:

🔹 Stop word removal

🔹 Tokenization

🔹 Lemmatization

🔹 Special character removal

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

Technique	Accuracy (%):

BoW	-      58%

TF-IDF	-  57%

Word2Vec -	57%

## 🔍 Observations:

- The classification task was challenging due to subjectivity in reviews and class imbalance.

- Basic models like Gaussian Naive Bayes may not capture semantic nuances in the text.

- The accuracy gap between techniques was narrow, indicating a need for more expressive models.

## 🚀 Learning Outcomes:

- Gained hands-on experience in NLP preprocessing and vectorization techniques.

- Understood the limitations of classical models for complex NLP tasks.

- Set the stage for experimenting with deep learning and transformer-based models like BERT for future improvements.

## 🧠 Takeaway:
This project served as a strong foundation in learning how to apply text vectorization methods and build classification models. While the results weren’t high, they highlight the challenges in real-world sentiment analysis and the need for more advanced models (like deep learning, transformers, or context-aware embeddings).

## 🚀 Let's Connect:

If you found this useful or want to collaborate, feel free to reach out!
🧑‍💻 Happy Learning!
