# 📚 Amazon Kindle Review Sentiment Analysis 🔍

This project explores a subset of the Amazon product reviews dataset (Kindle category) to analyze customer sentiment using a variety of text vectorization and machine learning techniques.

## 🧠 Project Objective

- **Understand** the sentiment behind product reviews 🗣️
- **Compare** the impact of different feature extraction and classification techniques on sentiment prediction performance 📊

## 🛠️ Techniques Used

We experimented with three popular Natural Language Processing (NLP) vectorization approaches:

- **Bag of Words (BoW)** 👜
- **TF-IDF (Term Frequency – Inverse Document Frequency)** 📈
- **Word2Vec Embeddings** 🧬

**Text preprocessing steps included:**
- 🔹 Special character removal
- 🔹 Stop word removal
- 🔹 Tokenization
- 🔹 Lemmatization

## 📦 Dataset Overview

- **Source:** Amazon Kindle Store Reviews (5-core version)
- **Entries:** 982,619 reviews
- **Time Span:** May 1996 – July 2014

**Features:**
- `reviewText` 📝 - Actual review text
- `rating` ⭐ - Review rating (1 to 5)

## 🤖 Models Compared

To evaluate the effect of different classifiers, we applied a range of machine learning models:

Models trained:
-------------
Logistic Regression   
XGBoost               
Support Vector Machine (SVM) 
Random Forest         
K-Nearest Neighbors (KNN)
Gaussian Naive Bayes 
Decision Tree

## 📊 Evaluation Metrics

Each model was assessed using:

- **Accuracy** 🎯
- **Classification Report** (Precision, Recall, F1-Score) 📄

## ✅ Results Summary

Here’s how the models performed using **Word2Vec embeddings**:

| Model                  | Accuracy (%) | Precision (macro) | Recall (macro) | F1-score (macro) |
|------------------------|-------------|-------------------|----------------|------------------|
| 🔗 Logistic Regression | **75.5**    | **72.9**          | 68.5           | 69.6             |
| 🚀 XGBoost             | 74.9        | 71.6              | **69.9**       | **70.5**         |
| 🧭 SVM                 | 75.0        | 72.6              | 67.3           | 68.5             |
| 🌳 Random Forest       | 74.7        | 71.4              | 68.9           | 69.7             |
| 👥 KNN                 | 72.0        | 67.9              | 65.8           | 66.4             |
| 🧮 GaussianNB          | 68.2        | 67.5              | 69.7           | 66.9             |
| 🌲 Decision Tree       | 67.3        | 62.8              | 62.7           | 62.8             |

> **Note:** BoW and TF-IDF with GaussianNB achieved around **58%** and **57%** accuracy, respectively.

## 🔍 Observations

- **Logistic Regression** and **XGBoost** outperformed other models, with Logistic Regression achieving the highest accuracy.
  
- **Word2Vec embeddings** provided a significant boost over BoW and TF-IDF when paired with more expressive classifiers.

- **GaussianNB**, while simple, lagged behind more advanced models, highlighting the importance of model selection in NLP tasks.
  
- The accuracy gap between classical vectorization (BoW/TF-IDF) and dense embeddings (Word2Vec) is substantial when using stronger classifiers.

## 🚀 Learning Outcomes

- Gained practical experience in **NLP preprocessing**, **vectorization**, and **model evaluation**.
  
- Learned that **model choice** dramatically impacts results, especially with richer feature representations.
  
- Identified the **limitations of classical models** and the potential of advanced approaches (e.g., deep learning, transformers like BERT) for future work.

## 🧠 Takeaway

This project built a solid foundation in text vectorization and machine learning for sentiment analysis. While classical models have their place, **modern embeddings and robust classifiers** are essential for tackling real-world NLP challenges. The next step? Experiment with deep learning and transformer-based models for even greater performance! ⚡

## 🤝 Let's Connect!

If you found this project insightful or would like to collaborate, feel free to reach out!

🧑‍💻 **Happy Learning and Coding!**
