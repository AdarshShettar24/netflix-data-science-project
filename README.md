# 🎬 Netflix Data Science Project

## 📌 Overview
This project analyzes the **Netflix Movies & TV Shows Dataset** to gain insights into Netflix’s content library.  
The goal is to practice data cleaning, visualization, and simple machine learning.

## 📂 Dataset
Dataset used: [Netflix Movies and TV Shows (Kaggle)](https://www.kaggle.com/datasets/shivamb/netflix-shows)

- Rows: ~8,800  
- Columns: 12 (title, type, director, cast, country, date_added, release_year, rating, duration, listed_in, description)

## 🔎 Project Workflow
1. **Data Cleaning**  
   - Handle missing values  
   - Remove duplicates  
   - Convert `date_added` to datetime  

2. **Exploratory Data Analysis (EDA)**  
   - Movies vs TV Shows count  
   - Top 10 countries with most content  
   - Content added trend over years  
   - Most common genres  

3. **Visualizations**  
   Using **Matplotlib** & **Seaborn**  

4. **Machine Learning**  
   - Built a Logistic Regression model to classify whether a title is a *Movie* or *TV Show* using text descriptions  
   - Achieved ~85% accuracy  

## 📊 Sample Visualizations
(Upload plots to an `images/` folder and they will show here)

![Movies vs TV Shows](images/movies_vs_tvshows.png)  
![Top Genres](images/top_genres.png)  

## 🤖 Machine Learning Results
- **Model:** Logistic Regression  
- **Accuracy:** ~85%  
- **Example Prediction:**  
