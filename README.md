# 📊 News Sentiment & Stock Price Movement Analysis

A mini end-to-end data analysis project combining **news sentiment**, **technical indicators**, and **market price movements**.
Built as part of an internship assessment showcasing skills in **Python**, **data preprocessing**, **EDA**, and **ML workflow structuring**.

---

## 🚀 Project Overview

The goal of this project is to explore whether **news sentiment** has a measurable relationship with **daily stock returns**.
This repo includes:

- ✔️ Web scraping (or dataset ingestion)
- ✔️ Text cleaning & preprocessing
- ✔️ Sentiment scoring
- ✔️ Stock price data loading
- ✔️ Feature engineering with technical indicators
- ✔️ Exploratory data analysis
- ✔️ Model preparation (Logistic Regression baseline)

This project focuses on **analysis, insights, and workflow clarity**, not just code.

---

## 📂 Repository Structure

```
project/
│
├── Scraper&Preprocessing/        # Raw scraping notebook and preprocessing scripts
├── postgreSQL Demo/              # Demo SQL scripts & sample database operations
├── notebooks/
│     ├── Sentiment_demo.ipynb    # Main analysis notebook
│     └── EDA.ipynb               # Optional exploratory notebook
├── data/
│     ├── news.csv                # Clean sentiment dataset (placeholder)
│     └── prices.csv              # Stock prices (placeholder)
├── models/
│     └── baseline_lr.pkl         # Optional saved model
│
└── README.md                     # You're reading it 😄
```

---

## 🧹 Preprocessing Steps

Key steps used before modeling:

1. **Clean Headlines**

   - Removed punctuation, HTML, emojis
   - Tokenization + stopword removal
   - Lemmatization

2. **Sentiment Extraction**

   - Using `[VADER / TextBlob / RoBERTa]`
   - Computed:

     - compound score
     - pos / neg / neu

3. **Feature Engineering**

   - Daily return calculation
   - Moving averages
   - RSI, MACD (optional)
   - Merging sentiment + price data

---

## 📈 Analysis Highlights

Some insights included in the notebook:

- Correlation between sentiment & next-day returns
- Sentiment patterns during volatile periods
- Return distributions
- Simple baseline model for up/down prediction

---

## 🛠️ Tech Stack

- **Python** (Pandas, NumPy, Scikit-Learn)
- **NLTK / HuggingFace** for sentiment
- **Matplotlib / Seaborn** for visuals
- **PostgreSQL** for querying and storing processed data

---

## ▶️ How to Run

```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo

pip install -r requirements.txt
```

Run the main notebook:

```
notebooks/Sentiment_demo.ipynb
```

---

## ✨ Future Improvements

- Add deep-learning based sentiment (FinBERT)
- Build a Streamlit dashboard
- Automate daily scraping + ETL pipeline
- Backtesting trading strategies

---

## 📮 Contact

If you want to collaborate or improve the project, feel free to open a PR or reach out!

Happy coding 🚀
