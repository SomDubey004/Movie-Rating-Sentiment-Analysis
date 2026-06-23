# 🎬 Movie Rating & Sentiment Analysis Dashboard

## 📌 Project Overview

This project analyzes movie data collected from the TMDB (The Movie Database) API and transforms it into an interactive dashboard using Python and Streamlit.

The project covers the complete data analytics workflow:

1. Data Collection using TMDB API
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Sentiment Analysis on Movie Overviews
5. Interactive Dashboard Development
6. Insight Generation

The dashboard helps users explore movie ratings, genres, languages, popularity, audience engagement, and sentiment trends.

---

# 🎯 Project Objectives

* Collect real-world movie data from TMDB API
* Clean and prepare the dataset for analysis
* Explore rating patterns and audience behavior
* Analyze genre and language trends
* Perform sentiment analysis on movie descriptions
* Build an interactive dashboard for stakeholders

---

# 🛠️ Tools & Technologies

### Programming

* Python

### Data Collection

* TMDB API
* Requests

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Plotly

### NLP

* TextBlob

### Dashboard

* Streamlit

---

# 🔍 Data Collection

Movie data was collected using the TMDB (The Movie Database) API.

### Data Fields Collected

* Movie ID
* Title
* Rating
* Vote Count
* Popularity
* Genres
* Original Language
* Release Date
* Overview

### API Workflow

1. Connect to TMDB API
2. Fetch movie records
3. Store raw JSON responses
4. Convert to DataFrame
5. Export as CSV

---

# 🧹 Data Cleaning

The following cleaning steps were performed:

* Removed duplicate Movie IDs
* Removed movies with zero ratings
* Handled missing values
* Removed blank values from text columns
* Fixed data types
* Created sentiment features
* Prepared dataset for dashboarding

### Final Dataset

* Movies: 953
* Features: 11

---

# 📊 Exploratory Data Analysis

Key analysis areas:

### Rating Analysis

* Rating distribution
* Top rated movies
* Rating statistics

### Genre Analysis

* Most common genres
* Highest rated genres
* Most popular genres
* Audience engagement by genre

### Language Analysis

* Most common languages
* Highest rated languages
* Audience engagement by language

### Sentiment Analysis

* Sentiment distribution
* Rating by sentiment
* Audience engagement by sentiment

---

# 🤖 Sentiment Analysis

Movie overviews were analyzed using TextBlob.

Sentiment categories:

* Positive
* Neutral
* Negative

Additional columns created:

* Sentiment Score
* Sentiment Category

---

# 📈 Dashboard Features

### Executive Overview

* KPI Cards
* Rating Distribution
* Top Rated Movies
![Streamlit Dashboard Executive Overview](F:\Screenshot\Screenshot 2026-06-23 164556.png)
*Screenshot of the Streamlit dashboard executive overview.*

### Genre Analysis

* Genre Popularity
* Genre Ratings
* Audience Engagement

### Language Analysis

* Language Distribution
* Language Ratings
* Audience Engagement

### Sentiment Analysis

* Sentiment Distribution
* Rating vs Sentiment
* Audience Engagement vs Sentiment

---

# 📸 Dashboard Screenshots

## Executive Overview

[Insert Screenshot Here]

---

## Genre Analysis

[Insert Screenshot Here]

---

## Language Analysis

[Insert Screenshot Here]

---

## Sentiment Analysis

[Insert Screenshot Here]

---

# 💡 Key Insights

* Most movie ratings fall between 6 and 8.
* Drama is the most common movie genre.
* English dominates the movie dataset.
* Positive sentiment movies receive slightly higher engagement.
* Audience engagement varies significantly across genres and languages.

---

# 🚀 Future Improvements

* Deploy dashboard on Streamlit Cloud
* Add movie recommendation system
* Integrate live TMDB API data
* Add advanced NLP techniques
* Add genre and language filters

---

# 👨‍💻 Author

Som Dubey

Aspiring Data Analyst

Skills: Python | SQL | Power BI | Pandas | Streamlit | Data Visualization

