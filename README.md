# 📰 Fake News Identifier

![Project Screenshot](https://github.com/Ranganath2525/fake-news-detector/blob/main/image.png)

## 📌 Overview
The **Fake News Identifier** is a machine learning-based system designed to detect whether a news article is **Authentic (Real)** or **Fake**.  
With the growing spread of misinformation across online platforms, this project leverages **Natural Language Processing (NLP)** and **Deep Learning** to automatically classify and flag misleading content.

---

## ✨ Features
- ✅ Classifies news as **Fake** or **Authentic**
- ✅ Uses **RoBERTa (Hugging Face Transformers)** for text classification
- ✅ Integrated with **News API** to fetch live articles
- ✅ Web Interface using **Flask, HTML, CSS**
- ✅ Real-time predictions with probability scores

---

## 🏗️ System Architecture
### 🔹 Frontend
- HTML, CSS, JavaScript
- Simple and responsive UI
- User input for news/articles

### 🔹 Backend
- Flask Framework
- News API integration
- Model inference using Hugging Face Transformers

### 🔹 Machine Learning
- Pre-trained **RoBERTa model**
- Trained on `fake.csv` and `true.csv` datasets
- Evaluated using Accuracy, Precision, Recall, and F1-Score

---

## 📂 Dataset
- **Fake.csv** → Contains fabricated news articles  
- **True.csv** → Contains authentic news articles  

### Preprocessing:
- Tokenization, Stopword Removal, Lemmatization  
- TF-IDF & Word Embeddings used  

---

## 📊 Results
- Achieved **~95% Accuracy** on test dataset  
- Balanced performance on **Fake vs Authentic** classes  
- Supports real-time detection of misinformation  

---

## 🚀 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Ranganath2525/fake-news-detector.git
   cd fake-news-detector
pip install -r requirements.txt
python fake_news_app.py
http://127.0.0.1:5000/
📸 Screenshots

Input news and check authenticity

Example outputs: Authentic, Fake, with related articles

🛠️ Tech Stack

Programming Language: Python

Framework: Flask

Frontend: HTML5, CSS3, JS

ML Library: Hugging Face Transformers, PyTorch

API: News API

📚 References

Hugging Face Transformers → GitHub

News API → Documentation

RoBERTa Paper: Liu et al., 2019

👨‍💻 Authors

Ranganath C (1JT22AI038)

Bhuvanesh Kumar G (1JT22AI006)

✅ Future Enhancements

🌐 Multilingual fake news detection

📊 Improved explainability using attention heatmaps

📱 Mobile app integration for on-the-go fact-checking
