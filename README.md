# 📊 Netflix Content Analysis using Power BI

## 📌 Overview

This repository contains a complete data analytics case study on Netflix movies and TV shows using **Power BI**.  
The project focuses on analyzing content trends, IMDb ratings, runtime patterns, and audience engagement over time through interactive visualizations, backed by a relational data model with a dedicated credits table for cast and crew analysis.

---

## 🔗 Project Resources

- 📁 **Dataset:**  
<https://docs.google.com/spreadsheets/d/13ERqbgW9hfzBkiot2rpgeXeaSzcYOdbz/edit?usp=sharing&ouid=102824183235186433803&rtpof=true&sd=true>

- 📄 **Case Study Report (PDF):**  
<https://drive.google.com/file/d/1XChsW80Xvim2CPM0WHREam99DwJo5UB3/view?usp=sharing>

---

## 📁 Dataset Summary

- **Total Records:** 5,850 titles
- **Content Types:** Movies and TV Shows
- **Time Period:** 1945 – 2022
- **Credits Table:** 77,801 rows of cast and crew data, linked to the main titles table for drill-through analysis

### Key Columns

- `id` – Unique identifier
- `title` – Content title
- `type` – Movie / TV Show
- `release_year` – Year of release
- `runtime` – Duration in minutes
- `imdb_score` – IMDb rating
- `imdb_votes` – IMDb vote count
- `age_certification` – Content rating

---

## 🧹 Data Cleaning & Transformation

All data preparation was performed using **Power Query Editor** in Power BI:

- Removed unnecessary columns (`index`, `imdb_id`)
- Retained rows with missing IMDb votes while excluding them from vote-based analysis
- Built a relational model linking the titles table to the 77,801-row credits table
- Restricted time-based trend analysis to **Movies only** to avoid bias caused by TV shows

---

## 📊 Business Questions Answered

1. Which movies and TV shows perform best by IMDb rating?
2. How has the number of movie releases changed over time?
3. How have average IMDb ratings for movies evolved over the last several decades?
4. Has audience voting activity on IMDb increased over time?
5. How has average runtime changed across decades?
6. How does age certification influence IMDb ratings?

---

## 📈 Visualizations Included

The Power BI dashboard contains the following visuals:

- Clustered Column Charts
- Line Charts
- Bar Charts
- Scatter Plots
- Drill-through pages from title-level visuals into cast/crew detail
- Interactive slicers for:
  * Release Year
  * Content Type

Each visualization was designed carefully to avoid misleading interpretations caused by uneven data distribution across years.

---

## 🧠 Key Insights

- Netflix content is heavily skewed toward releases after 2010 —
