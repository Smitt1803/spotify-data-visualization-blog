# 🎵 Spotify Data Visualization Blog

> Exploring Spotify Music Trends Through Data Visualization using **Google Sheets, Datawrapper, Flourish, RAWGraphs, and Google Looker Studio**.

![Status](https://img.shields.io/badge/Project-Completed-success)
![Visualization](https://img.shields.io/badge/Tools-5-blue)
![Dataset](https://img.shields.io/badge/Dataset-Spotify-green)

Blog: https://app.notion.com/p/Exploring-Spotify-Music-Trends-Through-Data-Visualization-3a059ad7cad08068b6b2ee927441a05d?source=copy_link

---

# 📖 Overview

Music streaming platforms generate massive amounts of data every day. Behind every song are numerous audio characteristics such as popularity, danceability, energy, acousticness, valence, tempo, and many more.

This project explores a Spotify dataset using **five different data visualization tools**, with each tool answering a different analytical question. Rather than relying on a single platform, the same dataset is analysed from multiple perspectives to demonstrate how different visualization tools reveal different insights.

The objective is not only to analyse Spotify music trends but also to compare the strengths of various visualization platforms for effective data storytelling.

---

# 🎯 Objectives

- Explore Spotify music trends using visual analytics.
- Compare the capabilities of five visualization tools.
- Identify patterns between popularity and audio characteristics.
- Understand differences among Spotify genres.
- Build an interactive dashboard for exploratory analysis.
- Demonstrate effective data storytelling techniques.

---

# 📂 Dataset

**Dataset:** Spotify Tracks Dataset

The dataset contains approximately **114,000 Spotify tracks** across **114 music genres**.

### Main Attributes

- Track Name
- Artist
- Genre
- Popularity
- Danceability
- Energy
- Acousticness
- Valence
- Tempo
- Loudness
- Explicit
- Speechiness
- Instrumentalness
- Liveness

---

# 🛠️ Tools Used

| Tool | Purpose |
|-------|----------|
| Google Sheets | Initial exploration and summary analysis |
| Datawrapper | Scatter plot and correlation analysis |
| Flourish | Radar chart comparing genre characteristics |
| RAWGraphs | Hexagonal binning for density visualization |
| Google Looker Studio | Interactive dashboard and filtering |

---

# 📊 Visualizations

## 1️⃣ Google Sheets

### Question

**Which Spotify genres are the most popular?**

### Visualization

Bar Chart showing the most popular Spotify genres.

<img width="1918" height="1018" alt="Google Sheets-1" src="https://github.com/user-attachments/assets/5f63c5a1-9d04-4b48-8997-ce97aab742b3" />


### Key Insights

- Pop-film achieved the highest average popularity.
- K-pop and Chill were among the top-performing genres.
- Genre popularity varies significantly across the dataset.
- Google Sheets provided a simple starting point for data exploration.

---

## 2️⃣ Datawrapper

### Question

**Do more danceable songs tend to be more popular on Spotify?**

### Visualization

Scatter Plot comparing **Danceability** and **Popularity**.

<img width="1918" height="1032" alt="Datawrapper-1" src="https://github.com/user-attachments/assets/0fbbfe9c-095d-41c2-9f93-267ca5a98765" />


### Key Insights

- A weak positive relationship exists between danceability and popularity.
- Many highly danceable songs still have low popularity.
- Popularity depends on several factors beyond danceability.
- Scatter plots effectively reveal correlations between variables.

---

## 3️⃣ Flourish

### Question

**How do the audio profiles of Spotify's most popular genres compare with one another?**

### Visualization

Radar Chart comparing:

- Energy
- Danceability
- Acousticness
- Valence

across the five most popular genres.

<img width="1918" height="1031" alt="Flourish-1" src="https://github.com/user-attachments/assets/1f8fc6a8-867f-45e3-97f7-394f71bb5e1d" />


### Key Insights

- Every genre has a distinct audio profile.
- Grunge shows higher energy.
- Sad music has higher acousticness.
- Radar charts make multi-variable comparisons easy.

---

## 4️⃣ RAWGraphs

### Question

**Where are the highest concentrations of Spotify tracks found when comparing Danceability and Popularity?**

### Visualization

Hexagonal Binning Plot

<img width="1918" height="1031" alt="RAWGraphs-1" src="https://github.com/user-attachments/assets/0d15d552-57e9-42bc-bdb1-0cf4a93f602f" />


### Key Insights

- Most tracks fall within lower popularity ranges.
- Danceability is widely distributed across songs.
- Hexagonal bins reduce overplotting.
- Density plots reveal hidden distribution patterns.

---

## 5️⃣ Google Looker Studio

### Question

**How can an interactive dashboard help users explore Spotify track popularity, genres, and audio characteristics?**

### Visualization

Interactive Dashboard including:

- KPI Cards
- Top Genres by Average Popularity
- Danceability vs Popularity Scatter Plot
- Genre Filter
- Popularity Slider
- Explicit Songs Filter

<img width="1918" height="1026" alt="Google Looker Studio-1" src="https://github.com/user-attachments/assets/bbf3bbb9-c41c-4dc3-83c3-1d1dcbba50b6" />


### Key Insights

- Dashboard enables dynamic exploration.
- Filters allow customised analysis.
- KPI cards summarise important statistics.
- Interactive dashboards improve user engagement.

---

# 🔍 Major Findings

- Pop-film has the highest average popularity.
- Danceability alone does not determine popularity.
- Different genres exhibit unique audio characteristics.
- Most Spotify songs belong to lower popularity ranges.
- Interactive dashboards provide the most flexible exploration experience.

---

# 📈 Dashboard Features

✔ KPI Cards

✔ Interactive Filters

✔ Genre Selection

✔ Popularity Range Slider

✔ Explicit Song Filter

✔ Ranking Charts

✔ Scatter Plot Analysis

---

# 📁 Project Structure

```
spotify-data-visualization-blog
│
├── README.md
├── images/
│   ├── google-sheets.png
│   ├── datawrapper.png
│   ├── flourish.png
│   ├── rawgraphs.png
│   └── looker-studio.png
│
├── dataset/
│   └── spotify-tracks.csv
│
└── blog/
    └── blog.pdf
```

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Analysis
- Data Visualization
- Dashboard Design
- Storytelling with Data
- Comparative Visualization
- Interactive Reporting

---

# 📚 References

- Spotify Tracks Dataset (Kaggle)
- Google Sheets
- Datawrapper
- Flourish
- RAWGraphs
- Google Looker Studio

---

# ✅ Conclusion

Each visualization tool contributed differently to understanding Spotify music trends. Google Sheets served as the foundation for data exploration, Datawrapper highlighted relationships between variables, Flourish compared multiple audio characteristics simultaneously, RAWGraphs revealed density patterns within large datasets, and Google Looker Studio combined these insights into a single interactive dashboard.

Using multiple visualization platforms demonstrated that selecting the right tool for the right analytical question significantly improves data storytelling. Together, these visualizations transformed raw Spotify data into meaningful insights that are easier to interpret, compare, and communicate.

---

# 👨‍💻 Author

**Smit Bharatbhai Vaghani**

B.Tech Artificial Intelligence & Machine Learning

Symbiosis Institute of Technology, Pune

---

⭐ *If you found this project interesting, consider giving the repository a star!*
