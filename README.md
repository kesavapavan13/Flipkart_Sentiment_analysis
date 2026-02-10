# 🛒 Flipkart Product Review Sentiment Analysis

A simple **Streamlit-based Machine Learning web app** that analyzes Flipkart product reviews and predicts whether the sentiment is **Positive 😊** or **Negative 😞** using a trained TF-IDF vectorizer and sentiment classification model.

---

## 📌 Project Overview

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to classify real-time product reviews.  
Users can enter any review text into the web interface, and the app will automatically:

- Clean and preprocess the text
- Convert text into TF-IDF vectors
- Predict sentiment using a trained model
- Display the result in a user-friendly UI

---

## 🚀 Features

- Streamlit interactive web interface
- Real-time sentiment prediction
- NLP preprocessing with NLTK
- TF-IDF text vectorization
- Pre-trained ML sentiment model
- Cached model loading for faster performance

---

## 🧠 Tech Stack

- Python
- Streamlit
- Scikit-learn
- NLTK
- Joblib
- Pandas & NumPy

---

## 📂 Project Structure

``` bash
📁 project-folder
│── app.py # Streamlit application
│── sentiment_model.pkl # Trained ML model
│── tfidf_vectorizer.pkl # Saved TF-IDF vectorizer
│── data.csv # Dataset (optional)
│── requirements.txt # Dependencies
│── README.md # Documentation

```


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/kesavapavan13/Flipkart_Sentiment_analysis
cd <project-folder>
```

### 2️⃣ Create Virtual Environment (Recommended)
```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### ▶️ Run the Application
```bash
streamlit run app.py
```

The app will open automatically in your browser.
---

## 📝 How It Works

1. User enters a Flipkart review.

2. Text is cleaned using:

  - Lowercasing

  - Regex filtering

  - Stopword removal

  - Lemmatization

3. TF-IDF vectorizer converts text to numerical features.

4. ML model predicts sentiment.

5. Result is displayed instantly.

## 📊 Model Information

- Vectorizer: TF-IDF

- Algorithm: Pre-trained ML classifier (saved as .pkl)

- Labels:

  - 1 → Positive

  - 0 → Negative

## 📦 Requirements

All dependencies are listed in:
```bash

requirements.txt
```

Install using:
```bash
pip install -r requirements.txt
```
## 💡 Future Improvements

Add confidence score

Support batch review upload

Deploy on Streamlit Cloud

Add Neutral sentiment class

Improve UI styling

## 👨‍💻 Author

Kesavapavan Gadde

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to contribute!

## 📂 Project Structure

