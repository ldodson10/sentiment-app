# Sentiment Analysis Web Tool 🧠

A Flask-based web application that detects and visualizes the emotional tone of text input. Users can track how they feel over time through a dynamic emotional feed and mood scoreboard.

---

## 🔍 What It Does

- Accepts user input (thoughts, journal entries, comments)
- Analyzes sentence-by-sentence sentiment (Positive 😊, Neutral 😐, Negative 😡)
- Stores all entries in a database
- Displays results with emojis, time stamps, and visual charts

---

## 🧱 Built With

- **Python** (Flask)
- **TextBlob** (NLP sentiment analysis)
- **HTML/CSS + Chart.js** (frontend UI & data viz)
- **SQLite** (database)
- **AWS EC2** (deployment)

---

## 📦 Features

- Emotional journaling & tracking
- Sentence-level analysis
- Visual scoreboard (positive/neutral/negative ratio)
- Database storage of all thoughts

---

## 🛠 Installation (Local)

```bash
git clone https://github.com/ldodson10/sentiment-app.git
cd sentiment-app
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python -m textblob.download_corpora
python app.py