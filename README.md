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

## 🚀 Project Tasks Completed

### ✅ Task 1: Data Collection & Preprocessing
- Scraped 1200+ reviews from Google Play Store
- Preprocessed: removed duplicates, handled missing values, normalized dates
- Saved as CSV with columns: `review_text`, `rating`, `review_date`, `bank`, `source`

### ✅ Task 2: Sentiment & Thematic Analysis
- Implemented sentiment analysis using `distilbert-base-uncased-finetuned-sst-2-english`
- Computed sentiment scores (positive/negative/neutral)
- Extracted keywords using TF-IDF
- Identified 3-5 themes per bank:
  - Account Access Issues
  - Transaction Performance  
  - User Interface & Experience
  - Customer Support
  - Feature Requests

### ✅ Task 3: PostgreSQL Database (Coming Soon)
- Database design with `banks` and `reviews` tables
- Schema for storing processed review data
- Python scripts for data insertion

### ✅ Task 4: Insights & Visualization (Coming Soon)
- Sentiment trends analysis
- Rating distributions
- Word clouds for each bank
- Actionable recommendations

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Web Scraping**: google-play-scraper
- **NLP**: HuggingFace Transformers, spaCy, NLTK
- **Database**: PostgreSQL, psycopg2
- **Visualization**: Plotly, WordCloud

## 📈 Key Insights (Preliminary)
1. **CBE**: High ratings (4.2) but complaints about slow transfers
2. **BOA**: Lower ratings (3.4) with login issues as major pain point
3. **Dashen**: Good ratings (4.1) with positive feedback on UI but occasional crashes

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/SeniyaSultan/Customer-Experience-Analytics-for-Fintech-Apps.git
cd Customer-Experience-Analytics-for-Fintech-Apps




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

