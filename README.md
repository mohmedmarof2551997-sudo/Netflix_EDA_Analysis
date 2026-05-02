# 🎬 Netflix Titles: Full EDA & KPI Dashboard

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3.0-red)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.0-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.0-green)
![Plotly](https://img.shields.io/badge/Plotly-5.1.0-purple)

## 📌 Project Overview

This project is a comprehensive **Exploratory Data Analysis (EDA)** of Netflix's content library using the `netflix_titles.csv` dataset. The goal is to uncover key insights into Netflix's content strategy, including content type distribution, country-wise production, genre trends, release patterns, and more.

📊 **Key Metrics Analyzed:**
- Total titles: 8,807
- Movies vs. TV Shows split
- Top content-producing countries
- Most popular genres
- Year-over-year growth trends
- Monthly release patterns
- Mature content percentage
- Median movie duration & TV seasons
- International vs. US content ratio

---

## 📁 Dataset Overview

| Column | Description |
|--------|-------------|
| `show_id` | Unique ID for each title |
| `type` | Movie or TV Show |
| `title` | Name of the title |
| `director` | Director(s) |
| `cast` | Main cast members |
| `country` | Country of production |
| `date_added` | Date added to Netflix |
| `release_year` | Original release year |
| `rating` | Content rating (PG-13, TV-MA, etc.) |
| `duration` | Duration (minutes or seasons) |
| `listed_in` | Genres |
| `description` | Short summary |

---

## 🔍 Key Insights

### 📈 Content Growth Over Time
- **Peak year of content addition:** 2019 (2,016 titles added)
- **YoY growth** surged between 2016–2019, slowed slightly during 2020–2021 (COVID impact)

### 🎭 Content Type Split
- **Movies:** 69.6% — dominate the platform
- **TV Shows:** 30.4% — growing segment in recent years

### 🌍 Top Content Producing Countries
| Country | Total Titles | Movies | TV Shows |
|---------|--------------|--------|----------|
| United States | 3,690 | 2,364 | 847 |
| India | 1,008 | 927 | 81 |
| United Kingdom | 628 | 382 | 246 |
| Canada | 271 | 187 | 84 |
| Japan | 259 | 85 | 174 |
| South Korea | 211 | 47 | 164 |

> 🔥 **South Korea** is a rising powerhouse in TV shows (K-Drama effect)

### 🧩 Top Genres
- **International Movies** – most frequent genre
- **Dramas, Comedies, Documentaries** – also highly represented

### 📅 Monthly & Seasonal Trends
- **July & December** — highest number of new titles added
- **February** — lowest additions (shortest month + post-holiday slowdown)

### 🕒 Duration & Seasonality
- **Median movie length:** 98 minutes
- **Median TV seasons:** 1 season
- **Single-season shows** make up ~67% of all TV content

### 🔞 Content Maturity
- **45.5%** of all titles are mature-rated (TV-MA, R, NC-17)

---

## 📊 Visualizations Included

1. **Content Type Pie Chart** – Movies vs. TV Shows
2. **Yearly Titles Added (Bar Chart)** – with labels
3. **Movies vs. TV Shows Over Time (Line Chart)**
4. **Monthly Content Addition Trends (Line + Bar)**
5. **Top 10 Countries – Total, Movies, TV Shows (Bar + Heatmap)**
6. **Correlation Heatmap** – numerical feature relationships
7. **YoY Growth Line Chart**
8. **Movie Duration & TV Seasons Distributions**

---

## 🛠️ Tools & Libraries Used

- `pandas` – data manipulation
- `numpy` – numerical operations
- `matplotlib` / `seaborn` / `plotly` – visualizations
- `datetime` – date processing

---

## 🧠 Skills Demonstrated

- Data cleaning & preprocessing (handling missing values, type conversion)
- Feature engineering (extracting year, month, duration, genre counts)
- KPI aggregation & dashboard creation
- Outlier detection using IQR
- Time series & trend analysis
- Country & genre-level segmentation
- Correlation analysis
- Storytelling with data visualizations

---

