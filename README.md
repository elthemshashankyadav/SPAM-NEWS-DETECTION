# 📌 SPAM News Detection

## 📖 Introduction
In today’s digital era, online platforms have revolutionized how news is shared and consumed. However, this shift has also given rise to **spam news**—misleading, irrelevant, or malicious content such as fake news, clickbait, disinformation, and misinformation. These can negatively impact societies by influencing elections, financial markets, public opinion, and even inciting violence.

This project implements a **Spam News Detection System** using **Machine Learning (ML)** and **Natural Language Processing (NLP)** techniques. The goal is to automatically classify news articles as **real** or **fake**, ensuring trustworthy information dissemination.

---

## 🚀 Features
- Preprocessing of text data (cleaning, tokenization, lemmatization).
- Feature extraction using **TF-IDF**.
- Classification using **Naive Bayes**.
- User input support for real-time prediction.
- Achieves good accuracy on labeled datasets.

---

## 🛠️ Tech Stack
- **Programming Language**: Python  
- **Libraries & Tools**:  
  - pandas, numpy  
  - nltk (for preprocessing & lemmatization)  
  - scikit-learn (ML models, TF-IDF, evaluation)  

---

## 📂 Dataset
- **True.csv** → Contains real news articles.  
- **Fake.csv** → Contains fake/spam news articles.  
- Both datasets are combined, preprocessed, and used for model training & testing.  

---

## 🔎 Methodology
1. **Data Preprocessing**  
   - Text cleaning (removing special chars, numbers, stopwords).  
   - Tokenization & lemmatization.  

2. **Feature Extraction**  
   - TF-IDF vectorization (unigrams & bigrams).  

3. **Model Training**  
   - Naive Bayes classifier trained on labeled data.  

4. **Prediction**  
   - User enters a news article → model predicts **True News** or **Fake News**.  

---

## 📊 Results
- The trained model achieved good accuracy on the test dataset.  
- It can predict new/unseen articles as either **real** or **spam**.  

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/spam-news-detection.git
   cd spam-news-detection
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the script:
   ```bash
   python spam_news_detection.py
4. Enter a news article when prompted → get prediction (True News / Fake News).
---



## 📌 Future Improvements

- Implement real-time detection for live news feeds.

- Extend to multilingual and multimodal data (text, images, videos).

- Use advanced models like Deep Learning (RNN, LSTM, Transformers).

- Improve UI/UX with a web app or mobile app interface.
-----
