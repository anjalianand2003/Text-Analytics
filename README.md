# Text-Analytics
# 🌾 FarmAds Text Classification

This project classifies text ads as **relevant** or **non-relevant** for a farming community website plagued by spam and irrelevant postings. We use **Natural Language Processing (NLP)** and **Machine Learning models** to automatically detect and filter out undesirable content.

## 📦 Dataset

- **File:** `FarmAds.csv`
- **Records:** 4,143 ads
- **Label:**
  - `1` — Relevant ad
  - `-1` — Non-relevant ad (spam, scam, or off-topic)
- **Text Column:** Contains raw advertisement content

---

## 🎯 Objective

To develop accurate models to classify ads using:
- 🔍 Naive Bayes
- ⚙️ Support Vector Machines (SVM)
- 🧹 Text preprocessing and dimensionality reduction

---

## 🧠 Methodology

### 1. Preprocessing

Performed using `tm` and `SnowballC`:
