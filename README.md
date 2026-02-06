# MBKM Sentiment Analysis on Twitter (X)

This repository contains a **sentiment analysis project** that examines public opinion toward the **Merdeka Belajar Kampus Merdeka (MBKM)** policy using Twitter (X) data.  
The project aims to identify dominant sentiments, key issues, and public responses related to the implementation of MBKM.

---

## Project Overview

- **Domain**: Natural Language Processing (NLP)
- **Task**: Sentiment Analysis (Multiclass Classification)
- **Data Source**: Twitter (X)
- **Language**: Python
- **Approach**: Supervised Machine Learning
- **Model**: Logistic Regression

---

## Objectives

- Analyze public sentiment toward MBKM policy
- Measure sentiment distribution (Positive, Neutral, Negative)
- Identify dominant topics discussed in each sentiment category
- Evaluate classification performance using **Macro F1-Score**

---

## Methodology

### 1. Exploratory Data Analysis (EDA)
- Analyze tweet distribution and sentiment proportions
- Identify class imbalance in sentiment labels

### 2. Text Preprocessing
The following preprocessing steps are applied:
- Case folding
- Removal of URLs, mentions, hashtags, numbers, and punctuation
- Stopword removal (Bahasa Indonesia)
- Stemming using **Sastrawi**

### 3. Feature Extraction
- Text representation using **TF-IDF Vectorization**
- Unigram and bigram features

### 4. Modeling
- **Logistic Regression** is used for sentiment classification
- Class weighting is applied to handle imbalanced data

### 5. Evaluation
Model performance is evaluated using:
- Accuracy
- Precision
- Recall
- **Macro F1-Score** (to fairly evaluate imbalanced classes)
- Confusion Matrix

### 6. Visualization
- Sentiment distribution bar chart
- WordCloud for each sentiment category

---

## Key Findings

- **Neutral sentiment dominates (52.3%)**, indicating that most tweets are informational, factual, or inquiry-based.
- **Positive sentiment (30.0%)** reflects substantial support for MBKM, especially regarding:
  - Internship opportunities
  - Practical experience
  - Flexibility in learning paths
- **Negative sentiment (17.5%)**, although smaller, highlights important concerns such as:
  - Bureaucratic complexity
  - Academic workload
  - Coordination between universities and external partners

---

## Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Sastrawi
- Matplotlib
- WordCloud

---

## Author
**Brikca Kristal Desfingka**

**Undergraduate Statistics Student at Universitas Gadjah Mada**

---
