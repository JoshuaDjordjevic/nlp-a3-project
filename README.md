41043: Natural Language Processing
---

# 📰 NLP for News Integrity: Classifying Misleading Headlines

This repository contains the code and resources for a project focused on classifying news article titles as either **fake** or **real** using Natural Language Processing (NLP) techniques.

## 📌 Project Summary

Fake news and clickbait headlines have become increasingly common in digital media. This project explores several NLP models — from classic machine learning classifiers to deep learning approaches — to detect misleading or deceptive article titles. The goal is to provide a lightweight yet accurate solution for automatic headline verification.

## 🧠 Models Implemented

* Naive Bayes Classifier
* Linear Regression (SGD Classifier)
* Support Vector Machine (SVM)
* TextCNN using BERT Tokenizer
* SVM on Full Article Body (for comparison)

## 📂 Dataset

We used the **WELFake** dataset, which includes over 72,000 labeled news articles sourced from multiple platforms (Kaggle, McIntire, Reuters, BuzzFeed).
→ [Kaggle Dataset Link](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification)

## 🚀 Getting Started

1. Clone the repo:

   ```bash
   git clone https://github.com/JoshuaDjordjevic/nlp-a3-project
   cd nlp-a3-project
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download dataset:

   * Download the **WELFake** dataset [here](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification) and copy it into `datasets/WELFake_Dataset.csv`.

4. Run the models:

   * Check out the individual notebooks (`naive_bayes.ipynb`, `support_vector_machine.ipynb`, `text_cnn.ipynb`, etc.)

## 📊 Results Summary

| Model              | Accuracy |
| -----------------  | -------- |
| Naive Bayes        | 87.81%   |
| Linear Regression  | 89.47%   |
| SVM                | 92.87%   |
| SVM (Full Article) | 97.44%   |
| TextCNN + BERT     | 92.76%   |

## 📎 Report & Presentation

See the full [project report (PDF)](link-to-pdf-if-hosted) for methodology, results, and discussion.

## 📌 Future Work

* Full article input support
* Integration with a browser extension or article credibility scoring tool
* Fine-tuning with full BERT embeddings

## 💻 Author

**Joshua Djordjevic**
This project was developed as part of an NLP university assignment.
