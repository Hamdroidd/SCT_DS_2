# SCT_DS_2
# 📺 Netflix Titles Dataset – Exploratory Data Analysis (EDA)

Welcome to the **Netflix EDA Project**, where we analyze trends, patterns, and insights from the official Netflix titles dataset. This project focuses on data cleaning, preprocessing, and rich visualization to uncover meaningful trends in Netflix's global content catalog.

---

## 📌 Project Objective

The aim of this project is to:
- Explore Netflix's movie and TV show offerings
- Understand trends over time, genres, countries, and durations
- Clean and preprocess real-world, messy data
- Create insightful visualizations for storytelling

---

## 📂 Dataset Description

**Source**: [`netflix_titles.csv`](https://www.kaggle.com/datasets/shivamb/netflix-shows)

| Column        | Description                                           |
|---------------|-------------------------------------------------------|
| `show_id`     | Unique ID for each show                               |
| `type`        | Type of content: Movie or TV Show                     |
| `title`       | Title of the show                                     |
| `director`    | Director(s)                                           |
| `cast`        | Main cast                                             |
| `country`     | Country of production                                 |
| `date_added`  | Date when the title was added to Netflix              |
| `release_year`| Release year                                          |
| `rating`      | TV/Movie rating (e.g., PG, TV-MA)                     |
| `duration`    | Runtime (minutes or seasons)                          |
| `listed_in`   | Genre categories                                      |
| `description` | Short synopsis                                        |

---

## 🧪 Steps Involved

### 1. **Data Loading & Inspection**
- Uploaded the CSV file and read it using `pandas`
- Explored the structure using `.info()`, `.head()`, and `.isnull()`

### 2. **Data Cleaning**[netflix_titles.csv](https://github.com/user-attachments/files/20943499/netflix_titles.csv)

- Converted `date_added` to datetime format
- Filled missing values with placeholders (`'Unknown'` or forward-filled)
- Extracted numerical duration for analysis

### 3. **Exploratory Data Analysis (EDA)**
Visualizations created using `seaborn` and `matplotlib`:

- 📊 **Content Type Distribution** – Movies vs. TV Shows
- 🌍 **Top 10 Countries** – Which countries produce the most content
- 📅 **Release Year Trends** – Number of titles added over time
- 🎭 **Top 10 Genres** – Most common genres on the platform
- ⏱ **Movie Duration Distribution** – Runtime spread of movies

---

## 📈 Sample Visualizations

- Content Type Distribution
- Country-wise Production
- Yearly Release Trends
- Genre Frequency
- Movie Length Histogram

---

## 🛠 Tools & Technologies

- Python 🐍
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Google Colab (or Jupyter Notebook)

---

## 🚀 How to Run This Project

1. Download the `netflix_titles.csv` file from Kaggle
2. Open [Google Colab](https://colab.research.google.com/)
3. Paste and run the full analysis code (provided separately)
4. Upload the CSV file when prompted
5. Run each cell to see the analysis

---

## 📌 Key Insights (Optional)

- Majority of Netflix content is **Movies**
- The **USA, India, and UK** dominate content production
- **Dramas and International Movies** are top genres
- Content growth spiked significantly after 2015
- Most movies have a duration around **90–100 minutes**

---

## 📚 Future Enhancements

- Add word clouds from titles/descriptions
- Build a recommendation engine
- Compare Netflix with other platforms (Prime, Hulu, etc.)
- Interactive dashboards (e.g., using Plotly or Streamlit)

---
[netflix_titles.csv](https://github.com/user-attachments/files/20943526/netflix_titles.csv)
