# 🎬 Netflix Movies & TV Shows — Exploratory Data Analysis

[![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)](.)
[![Type](https://img.shields.io/badge/Type-EDA-purple?style=for-the-badge)](.)

> Exploratory Data Analysis on Netflix's content library — uncovering trends in content type, genres, ratings, country contributions, and release patterns to understand how Netflix has built its global entertainment empire.

---

## 📌 Table of Contents.

- [Project Overview](#-project-overview)
- [Dataset Description](#-dataset-description)
- [Tools & Technologies](#️-tools--technologies)
- [Project Structure](#-project-structure)
- [Key Analysis Performed](#-key-analysis-performed)
- [Key Insights](#-key-insights)
- [Visualizations](#-visualizations)
- [Conclusions](#-conclusions)
- [Future Work](#-future-work)
- [Author](#-author)

---

## 🔍 Project Overview

Netflix is the world's leading streaming platform with 200M+ subscribers across 190+ countries. Understanding **what kind of content Netflix produces, from where, for whom, and when** is a powerful business intelligence exercise.

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on Netflix's titles dataset to:

- Understand the split between Movies and TV Shows
- Identify dominant genres, ratings, and content categories
- Analyze year-over-year content growth trends
- Explore country-level content contributions
- Discover top directors and most-featured cast members
- Extract actionable insights about Netflix's content strategy

---

## 📁 Dataset Description

> 📂 Source: [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

The dataset contains **8,807 titles** available on Netflix as of mid-2021.

| Feature | Description |
|---|---|
| `show_id` | Unique ID for each title |
| `type` | Movie or TV Show |
| `title` | Name of the title |
| `director` | Director(s) |
| `cast` | Featured cast members |
| `country` | Country of production |
| `date_added` | Date added to Netflix |
| `release_year` | Original release year |
| `rating` | Content rating (TV-MA, PG-13, etc.) |
| `duration` | Duration in minutes (movies) or seasons (TV shows) |
| `listed_in` | Genre(s) |
| `description` | Brief description |

---

## 🛠️ Tools & Technologies

- **Language:** Python 3.8+
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## 📂 Project Structure

```
Netflix_EDA/
│
├── Netflix_EDA.ipynb                    # Main analysis notebook
├── Netflix_EDA_Report.pdf               # Detailed PDF report
├── README.md                            # Project documentation
├── netflix_titles.csv                   # Dataset (download from Kaggle)
└── visualizations/
    ├── viz_content_type.png
    ├── viz_rating_dist.png
    ├── viz_top_genres.png
    ├── viz_rating_by_type.png
    ├── viz_movie_duration.png
    ├── viz_yearly_additions.png
    ├── viz_monthly_pattern.png
    ├── viz_top_countries.png
    └── viz_directors_cast.png
```

---

## 📈 Key Analysis Performed

- **Data Cleaning & Preprocessing** — Handling missing values, date parsing, feature extraction
- **Content Type Analysis** — Movies vs TV Shows distribution
- **Rating Analysis** — Distribution of content ratings across types
- **Genre Analysis** — Top genres and multi-genre breakdown
- **Bivariate Analysis** — Rating by content type, duration patterns
- **Trend Analysis** — Year-over-year and month-wise content additions
- **Geographic Analysis** — Top content-producing countries
- **People Analysis** — Top directors and most-featured cast members

---

## 🔑 Key Insights

1. 🎬 **Content Split** — Netflix's library is ~69% Movies and ~31% TV Shows, showing a clear preference for film content
2. ⭐ **Ratings** — TV-MA and TV-14 dominate — Netflix is primarily an adult content platform
3. 🎭 **Genres** — International Movies, Dramas, and Comedies are the top three genres, reflecting Netflix's global expansion strategy
4. 📅 **Growth Peak** — Content additions peaked in 2019-2020; a dip in 2021 likely reflects COVID-19 production slowdowns
5. 📆 **Monthly Pattern** — January and July see the highest content additions — aligning with post-holiday and summer viewing peaks
6. 🌍 **Geographic Dominance** — The USA contributes the most content by a large margin; India ranks 2nd, highlighting strong investment in South Asian markets
7. 🎞️ **Movie Duration** — Average Netflix movie is ~99 minutes; most fall in the 80–120 minute sweet spot
8. 🎥 **Directors** — A small group of prolific directors contributes a disproportionately large share of Netflix's catalog

---

## 📊 Visualizations

The notebook includes 9 visualizations:-

- Content type pie chart & bar chart
- Rating distribution bar chart
- Top 15 genres horizontal bar chart
- Rating by content type grouped bar chart
- Movie duration histogram with mean/median lines
- Yearly content addition trend (2010–2021)
- Monthly content addition line chart
- Top 12 countries bar chart
- Top 10 directors & cast side-by-side comparison

---

## ✅ Conclusions

This analysis reveals that Netflix's content strategy is built on:

- **Volume over niche** — massive catalog across all genres and ratings
- **Global-first thinking** — heavy investment in international content, especially from India
- **Adult audience focus** — majority of content is TV-MA or TV-14
- **Aggressive growth** — near-exponential content additions from 2015 to 2020
- **Seasonal strategy** — content drops timed around January and July for maximum viewership

---

## 🚀 Future Work

- Sentiment analysis on title descriptions using NLP
- Recommendation system based on genres and ratings
- Time-series forecasting of content addition trends
- Comparison with competitor platforms (Disney+, Prime Video)

---

## 👤 Author

**Mayank Yadav**
- 🔗 [LinkedIn](https://www.linkedin.com/in/mayank-yadav-82a6a6211)
- 🐙 [GitHub](https://github.com/Mayank-589)
- 📧 mayankyadavj589@gmail.com

---

> ⭐ If you found this project helpful, consider giving it a star!
