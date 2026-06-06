# 🎭 Task 4 — Sentiment Analysis
### Oasis Infobyte | Data Analytics Internship | Level 1

![Task](https://img.shields.io/badge/Task-4-purple?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-1-pink?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Data%20Analytics-blueviolet?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 👩‍💻 Intern Details

| Field | Details |
|-------|---------|
| **Name** | Maddali Naga Durga Niharika |
| **College** | Vasireddy Venkatadri Institute of Technology (VVIT) |
| **Internship ID** | OIB/A2/IP5267 |
| **Organization** | Oasis Infobyte |
| **Domain** | Data Analytics |
| **GitHub** | [maddali23/OIBSIP](https://github.com/maddali23/OIBSIP) |

---

## 📌 Project Overview

| Field | Details |
|-------|---------|
| **Project Title** | Sentiment Analysis on Text Data |
| **Level** | Level 1 — Task 4 |
| **Dataset 1** | Twitter US Airline Sentiment (Kaggle) |
| **Dataset 2** | IMDB Movie Reviews — 50K (Kaggle) |
| **Tools Used** | Python, Pandas, NumPy, Matplotlib, Seaborn, NLTK, Scikit-learn |
| **Platform** | Google Colab |

---

## 🎯 Objective

To develop a sentiment analysis model that accurately classifies the sentiment of text data as **Positive**, **Negative**, or **Neutral** — providing valuable insights into public opinion, customer feedback, and social media trends.

---

## 📂 Datasets Used

| # | Dataset | Source | Size |
|---|---------|--------|------|
| 1 | Twitter US Airline Sentiment | [Kaggle](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment) | ~14,640 rows |
| 2 | IMDB Movie Reviews (50K) | [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) | ~50,000 rows |

---

## 🪜 Steps Performed

| Step | Task | Description |
|------|------|-------------|
| 1️⃣ | **Data Loading** | Loaded both datasets into Pandas DataFrames using Google Colab |
| 2️⃣ | **Data Exploration** | Checked shape, columns, sentiment distribution, and missing values |
| 3️⃣ | **Sentiment Visualization** | Plotted Pie charts to show sentiment distribution for both datasets |
| 4️⃣ | **Text Preprocessing** | Cleaned text — removed URLs, mentions, hashtags, punctuation, stopwords; applied lemmatization |
| 5️⃣ | **Word Cloud** | Generated Word Clouds for positive and negative sentiments on both datasets |
| 6️⃣ | **TF-IDF Vectorization** | Converted cleaned text into numerical features using TF-IDF (max 5000 features, bigrams) |
| 7️⃣ | **Model Building** | Trained Naive Bayes and Logistic Regression models on both datasets |
| 8️⃣ | **Model Evaluation** | Evaluated using Accuracy Score, Classification Report, and Confusion Matrix |
| 9️⃣ | **Model Comparison** | Compared Naive Bayes vs Logistic Regression accuracy using Bar charts |
| 🔟 | **Custom Predictions** | Tested models on custom text inputs to predict sentiment in real-time |

---

## 🔑 Key Concepts Covered

| # | Concept | What I Did |
|---|---------|------------|
| 1 | **Sentiment Analysis** | Analyzed text data to determine emotional tone — Positive, Negative, Neutral |
| 2 | **NLP — Text Preprocessing** | Removed noise, applied stopword removal and lemmatization |
| 3 | **TF-IDF Vectorization** | Converted text to numerical features for ML model input |
| 4 | **Machine Learning Models** | Implemented Naive Bayes and Logistic Regression for classification |
| 5 | **Feature Engineering** | Used bigrams (ngram_range 1-2) to capture word pairs as features |
| 6 | **Data Visualization** | Created Pie charts, Word Clouds, Confusion Matrix heatmaps, and Bar charts |



## 📈 Visualizations

| # | Visualization | Description |
|---|--------------|-------------|
| 1 | 🥧 Sentiment Distribution | Pie charts showing positive/negative/neutral split |
| 2 | ☁️ Word Cloud | Most frequent words in positive and negative sentiments |
| 3 | 🔥 Confusion Matrix | Heatmap showing correct vs incorrect predictions |
| 4 | 📊 Model Comparison | Bar chart comparing Naive Bayes vs Logistic Regression accuracy |

---

## 💡 Key Insights

| # | Insight |
|---|---------|
| 🐦 | Twitter data had **mostly negative** sentiments about airlines |
| 🎬 | IMDB reviews were **evenly split** between positive and negative |
| 😊 | Words like *"great", "love", "best"* dominated positive sentiments |
| 😡 | Words like *"worst", "terrible", "waste"* dominated negative sentiments |
| 🤖 | **Logistic Regression** gave better accuracy than Naive Bayes on text data |

---

## 🧠 What I Learned

- Text data must be **preprocessed** before feeding into ML models — removing noise is critical
- **TF-IDF Vectorization** effectively converts raw text into meaningful numerical features
- **Logistic Regression** outperforms Naive Bayes for complex sentiment classification tasks
- **Word Clouds** are a powerful way to visually understand dominant words in each sentiment
- **Confusion Matrix** helps identify which classes the model struggles to classify correctly
- **Bigrams** (ngram_range 1-2) capture context better than single words alone
- Real-world text data has a lot of noise — URLs, mentions, punctuation must be cleaned first

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=for-the-badge)
![NLTK](https://img.shields.io/badge/NLTK-154f3c?style=for-the-badge)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

---

## 🔗 Links

| Resource | Link |
|----------|------|
| 📓 Project Notebook | [MaddaliNagaDurgaNiharika_Task4.ipynb](https://github.com/maddali23/OIBSIP/tree/main/Task4) |
| 🐙 GitHub Repository | [maddali23/OIBSIP](https://github.com/maddali23/OIBSIP) |
| 🎥 Demo Video | [Add your LinkedIn post link here](#) |

---

*Task 4 — Sentiment Analysis | Oasis Infobyte Data Analytics Internship*
*Intern: Maddali Naga Durga Niharika | VVIT | May 2026*
