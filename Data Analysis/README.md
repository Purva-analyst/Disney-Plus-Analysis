# 🎬 Disney+ Titles Analysis

This project explores the **Disney+ dataset** with Exploratory Data Analysis (EDA).  
We clean the data, visualize trends, and generate insights about movies and TV shows.

---
## 📂 Project Structure

Disney-Plus-Analysis/
│
├── data/ # Dataset
├── notebooks/ # Jupyter notebook(s)
├── images/ # Graphs and plots
├── requirements.txt # Libraries required
└── README.md # Project summary

--------------

## 🛠️ Steps Done
### 1. Data Cleaning
- Removed duplicates & null values.
- Converted `duration` column → numeric (`minutes` or `seasons`).
- Standardized ratings and country values.

### 2. Exploratory Data Analysis (EDA)
- **Counts of Movies vs TV Shows**  
- **Distribution of ratings**  
- **Movie durations vs TV seasons**  
- **Scatter plot: Rating vs Duration**  
- **Content trend per year**

### 3. Insights
- Movies dominate the platform, but TV shows are growing.  
- US produces the highest number of titles, followed by other countries.  
- Typical movie length: ~100 minutes.  
- Most common genres: Family, Comedy, Drama.  

---

## 📊 Visualizations

### Movies vs TV Shows
![Movies vs TV Shows](image/movies_vs_tvshows.png)

### Titles per Rating
![Titles per Rating](image/titles_per_rating.png)

### Movie Durations
![Movie Durations](image/movie_durations.png)

### Scatter Plot: Rating vs Duration
![Scatter Plot](image/scatter_rating_duration.png)

### Content Trend Over the Years
![Trend](image/Top_10_disney+_genres.png)

### TV SHow Duration
![Trend](image/TV_show_duration.png)

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/Purva-analyst/Disney-Plus-Analysis.git
   cd Disney-Plus-Analysis

2.Install requirements:

	pip install -r requirements.txt


3.Open the notebook:

	jupyter notebook notebooks/Disney_plus_analysis.ipynb