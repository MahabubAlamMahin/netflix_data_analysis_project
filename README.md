# netflix_data_analysis_project


# 🎬 Netflix Movies Genre Analysis Project

This project performs a complete exploratory data analysis on a curated Netflix movies dataset, focusing on genres, popularity trends, and release patterns. The dataset was cleaned, transformed, and enriched to uncover deeper insights about Netflix's content strategy.

## 📁 Dataset
- **Total Records**: 9,826 entries (expanded to 25,551 after genre normalization)
- **Source**: [Custom/Kaggle dataset] *(provide link if available)*

## 🧠 Objectives
- Clean and structure data for analysis
- Extract and normalize multi-genre data
- Categorize popularity for better interpretability
- Discover genre and year-wise trends

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔧 Data Cleaning & Preprocessing
- Converted `Release_Date` from string to datetime (dd-mm-yyyy → year only)
- Removed irrelevant columns: `Overview`, `Original_Language`, `Poster_Url`
- Categorized `vote_average` into: `Not Popular`, `Below Average`, `Average`, `Popular`
- Dropped 100 rows with null popularity values
- Normalized multi-genre rows: split genre list into individual rows (expanded dataset from 9,826 to 25,551 rows)
- Converted `Genre` column to category datatype for optimization

## 📊 Key Insights
- 🎭 **Drama** is the most frequent genre on Netflix.
- 🕷️ **Spider-Man: No Way Home** is the most popular movie (`Popularity Score: 5083.954`) — Genres: Action, Adventure, Science Fiction
- 🎶 **The United States vs. Billie Holiday** and **Thread** are the least popular movies.
- 📅 **2021** saw the highest number of releases with **1,636 movies**.

## 📈 Visualizations
- Genre distribution bar chart
- Popularity trends
- Movie count by year


