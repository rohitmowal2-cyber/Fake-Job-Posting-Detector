# 🔍 Fake Job Posting Detector

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![ML](https://img.shields.io/badge/ML-Classification-green)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-purple)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Problem Statement

Millions of job seekers fall victim to fake job postings every year, leading to financial fraud and data theft. This project uses **Machine Learning + NLP** to automatically classify whether a job listing is **fraudulent or legitimate** — helping users stay safe in their job search.

---

## 📊 Dataset

- **Source:** [Kaggle — Real/Fake Job Postings](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)
- **Records:** 17,880 job postings
- **Features:** 18 (text + structured)
- **Target Variable:** `fraudulent` (0 = Legitimate, 1 = Fake)

---

## 🔧 Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas, NumPy | Data manipulation |
| Matplotlib, Seaborn | Data visualization |
| Scikit-learn | ML models & evaluation |
| XGBoost | Best performing model |
| TF-IDF | Text feature extraction (NLP) |

---

## ⚙️ Approach

1. **Exploratory Data Analysis (EDA)** — Class imbalance analysis, missing value check, fraud patterns by location
2. **Text Cleaning** — Removed HTML tags, URLs, punctuation, and stopwords
3. **Feature Engineering** — TF-IDF vectorization (5000 features) combined with structured features
4. **Model Training** — Trained 3 classification models
5. **Evaluation** — Compared using Accuracy, ROC-AUC, and Confusion Matrix

---

## 📈 Model Results

| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 95.2% | 0.961 |
| Random Forest | 97.5% | 0.981 |
| **XGBoost ✅ Best** | **98.1%** | **0.989** |

---

## 📂 Project Structure
