# Netflix-Python-Project
Awesome work! Based on all the great exploration and visualizations you’ve done, here’s a clean, professional, and engaging `README.md` you can use for your **Netflix Data Analysis Project** on GitHub:



# 🎬 Netflix Movies Data Analysis with Python

This project explores a Netflix-style movie dataset using Python, diving into trends, patterns, and insights using data cleaning, feature engineering, and visualization techniques.



## 📂 Dataset Overview

- **Source**: [Kaggle - Netflix Movies & TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) *(or your own curated movie dataset)*
- **Size**: 9,827 entries, 9 columns
- **Key Features**:
  - Title, Release Date
  - Popularity, Vote Count, Vote Average
  - Genres (multi-labeled)
  - Language, Overview, Poster URL



## 🔧 Tools & Technologies

- **Python** 🐍
- **Pandas**, **NumPy** – data cleaning & wrangling
- **Matplotlib**, **Seaborn** – data visualization
- **Jupyter Notebook** – exploration & storytelling



## 📊 Objectives

- Clean and preprocess the movie dataset
- Create meaningful categorizations (e.g. vote-based popularity)
- Split and normalize multi-genre data
- Visualize:
  - Most frequent genres
  - Vote average distribution
  - Popularity trends
  - Year-wise movie counts
- Identify outliers and top/bottom performers



## 🧹 Data Cleaning Highlights

- Converted `Release_Date` to **year**
- Removed unused columns like `Overview`, `Original_Language`, `Poster_URL`
- Handled multi-label `Genre` column using `.str.split()` and `.explode()`
- Categorized `Vote_Average` into custom bins:  
  `not_popular`, `below_avg`, `average`, `popular`


## 📈 Key Visual Insights

### 🎭 Most Frequent Genre  
📌 **Drama** is the most dominant genre, appearing in over **14%** of entries.

### 🔥 Highest Voted Genres  
Genres like **Drama** and **Thriller** dominate the *popular* vote average category.

### 🕷️ Most Popular Movie  
- **Spider-Man: No Way Home** tops the chart with a popularity score over **5000**  
- Genres: *Action, Adventure, Science Fiction*

### 🧊 Least Popular Movie  
- **Threads (1984)** and *The United States vs. Billie Holiday (2021)* had the lowest popularity.

### 📆 Movie Boom Years  
- **2020** had the highest number of releases in the dataset.



## 📌 Sample Questions Answered

| # | Question | Answer |
|--|----------|--------|
| Q1 | What is the most frequent genre? | Drama |
| Q2 | What genre has highest vote average? | Drama, Thriller |
| Q3 | Highest popularity movie? | *Spider-Man: No Way Home* |
| Q4 | Lowest popularity movie? | *Threads*, *The United States vs. Billie Holiday* |
| Q5 | Year with most movie releases? | 2020 |



## 📁 Folder Structure

```
├── netflix_data_analysis.ipynb
├── mymoviedb.csv
├── README.md



## 🚀 Run the Project

1. Clone the repo
2. Install requirements (e.g. pandas, matplotlib, seaborn)
3. Launch the notebook:
   ```bash
   jupyter notebook netflix_data_analysis.ipynb
   ```



## 🙌 Acknowledgments

Thanks to open-source communities and [Kaggle](https://www.kaggle.com) for making data freely accessible for learning and exploration.




