# 🎬 TMDB Movie NLP Preprocessing Project

## 📌 Overview

This project demonstrates how to fetch movie data from the TMDB API and perform **NLP preprocessing** using Python libraries like NLTK and spaCy.

The goal is to build a strong foundation for tasks like:

* Text cleaning
* Tokenization
* Feature extraction
* Movie recommendation systems

---

## 🚀 Features

* Fetch real-time movie data from TMDB API
* Convert JSON data into structured Pandas DataFrame
* Perform text preprocessing on movie overviews
* Tokenization using NLTK and spaCy
* Stemming using PorterStemmer
* Basic NLP pipeline implementation

---

## 🛠️ Tech Stack

* Python
* Pandas
* Requests
* NLTK
* spaCy
* Scikit-learn

---

## 📂 Dataset

Data is fetched dynamically using TMDB API:

* Popular movies
* Includes title, overview, language, rating, etc.

---

## ⚙️ Workflow

### 1. Data Collection

* Fetch movie data using TMDB API
* Convert JSON → Pandas DataFrame

### 2. Data Cleaning

* Handle missing values
* Select relevant columns
* Rename columns for clarity

### 3. NLP Preprocessing

* Lowercasing text
* Tokenization
* Removing punctuation
* Stemming words

### 4. Feature Preparation

* Prepare text for vectorization (TF-IDF)

---

## 🧠 Example

### Input:

```
"I love learning NLP!"
```

### Output (after preprocessing):

```
['I', 'love', 'learning', 'NLP']
```

---

## ⚠️ Limitations

* Stemming may produce unnatural words
* Tokenization alone is not sufficient for full NLP pipeline
* Performance can be slow if not optimized (use spaCy pipe for large data)

---

## 🔥 Future Improvements

* Add lemmatization instead of stemming
* Use TF-IDF or word embeddings
* Build a movie recommendation system
* Optimize processing using spaCy `nlp.pipe()`

---



---

## ▶️ How to Run

1. Add your TMDB API key
2. Run the Jupyter Notebook
3. Execute cells step by step

---

## 🎯 Learning Outcomes

* Understanding NLP preprocessing pipeline
* Difference between tokenization and stemming
* Working with real-world API data
* Preparing text data for ML models

---

## 📌 Author

Amit Kumar Singh Kurmi

---

