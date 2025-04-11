# 📰 Fake News Classifier

This project is a **Fake News Detection** system built using Natural Language Processing (NLP) techniques and a Logistic Regression model. It achieves an accuracy of **92–93%** on real-world news data.

---

## 🚀 Features

- ✅ Detects whether a given news article is **fake** or **real**
- 🔍 Uses NLP libraries like **NLTK** and **spaCy** for preprocessing
- 📊 Trained with **Logistic Regression** model
- 🧠 Achieves over **92% accuracy** on the test set

---

## 🛠️ Technologies Used

- Python
- scikit-learn
- NLTK
- spaCy
- Pandas / NumPy

---

## 🧪 How It Works

1. **Text Preprocessing** using:
   - Tokenization (NLTK / spaCy)
   - Stopword Removal
   - Lemmatization

2. **Vectorization**:
   - `CountVectorizer` or `TfidfVectorizer`

3. **Modeling**:
   - Logistic Regression using `scikit-learn`

4. **Evaluation**:
   - Accuracy, Precision, Recall, F1 Score

---

## 📈 Accuracy

- ✅ **Test Accuracy**: ~92–93%
- 📉 The model is evaluated using proper train-test split and cross-validation.

---

## 💻 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/fake-news-classifier.git
   cd fake-news-classifier
