# 🛍️ Fashion PDP Recommendation Engine

## 📌 Problem Statement

Users often leave product pages if they don’t find relevant alternatives.
This project builds a **“Similar Products” recommendation system** for Product Detail Pages (PDP) to improve engagement and conversion.

---

## 🎯 Solution

A content-based recommendation engine that suggests similar products using:

* Category
* Brand
* Color
* Price bucket
* Product name (TF-IDF)

---

## 🧠 Approach

### 1. Feature Engineering

* Combined product attributes into text features
* Created price buckets

### 2. Model

* TF-IDF Vectorization
* Cosine Similarity

### 3. Recommendation Logic

* Compute similarity between products
* Return Top-K similar items

---

## 🖥️ Demo

(Add screenshot here)

---

## ⚙️ Tech Stack

* Python
* Pandas
* Scikit-learn
* Streamlit

---

## 📊 Evaluation

* Feature overlap analysis (Category, Brand, Color, Price)
* Coherence-based evaluation due to lack of user interaction data

---

## 🚀 Future Improvements

* Embedding-based recommendations (OpenAI)
* Hybrid recommender system
* Real-time personalization
* A/B testing framework

---

## 💡 Product Thinking

If deployed in production, this system could:

* Increase CTR on PDP by 10–15%
* Reduce drop-offs
* Improve product discovery

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```
