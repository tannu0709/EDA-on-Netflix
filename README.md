# 🎬 Netflix Data Analysis & Visualization (EDA)

## 📖 Overview

This project performs **Exploratory Data Analysis (EDA)** on Netflix data using both **Python (Pandas)** and **SQL** to uncover trends, patterns, and insights. on the Netflix Movies and TV Shows dataset to uncover trends in content distribution, growth patterns, genres, and audience targeting.

The analysis focuses on transforming raw data into meaningful insights using **data cleaning, visualization, and statistical reasoning**.

---

## 📊 Dataset

- Source: Netflix Movies and TV Shows Dataset
- Records: ~8800+ titles
- Features include:
  - Title, Type (Movie/TV Show)
  - Director, Cast, Country
  - Release Year, Date Added
  - Rating, Duration, Genre

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔗 Workflow

```
CSV → Data Cleaning (Pandas) → SQL Database → Querying → Visualization → Insights
```

## 🔍 Data Preprocessing

- Handled missing values in `director`, `cast`, `country`, and `rating`
- Converted `date_added` to datetime format
- Extracted `year_added` for time-based analysis
- Cleaned and transformed `duration` for numerical analysis
- Split multi-value columns like `genres` and `country`

---

## 📈 Analysis Performed

### 1. Content Distribution

- Comparison between Movies and TV Shows
- Percentage-based insights

### 2. Time-Based Analysis

- Growth of Netflix content over the years
- Comparison of Movies vs TV Shows over time

### 3. Country-Based Analysis

- Top content-producing countries
- Country vs content type comparison

### 4. Genre Analysis

- Most common genres on Netflix
- Genre distribution across Movies and TV Shows

### 5. Duration Analysis

- Distribution of movie durations
- Identification of common runtime patterns

### 6. Content Freshness

- Difference between release year and Netflix addition year
- Understanding whether Netflix favors newer or older content

### 7. Correlation Analysis

- Relationship between numerical features using heatmap

### 8. SQL-Based Analysis

- Queried structured data using SQL
- Compared SQL and Pandas workflows
- Extracted insights using aggregation queries

---

## 🗄 SQL Integration

- Converted dataset into SQLite database
- Performed data analysis using SQL queries
- Used GROUP BY, ORDER BY, and filtering
- Integrated SQL results with Pandas for visualization

## 📌 Key Insights

- Netflix catalog is dominated by **Movies**, but **TV Shows have grown rapidly after 2016**
- **USA and India** are the top content-producing countries
- Content additions increased significantly after **2015**, showing platform expansion
- **Drama and International genres** are the most prevalent
- Most movies fall within **90–120 minutes duration**
- Netflix includes both **recent and older content**, maintaining a diverse library

---

## 📁 Project Structure

```
netflix-eda/
│
├── netflix_eda.ipynb      # EDA using Pandas
├── netflix_sql.ipynb      # SQL-based analysis
├── netflix.db             # SQLite database
├── images/
├── README.md
```

## 🚀 Future Improvements

- Build an interactive dashboard using Streamlit
- Add advanced visualizations (Seaborn/Plotly)
- Integrate external datasets (e.g., IMDb ratings)
- Deploy as a web-based analytics tool
