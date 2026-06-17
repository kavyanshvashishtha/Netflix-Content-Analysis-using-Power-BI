# 📊 Netflix Content Analysis using Power BI

## 📌 Overview
This repository contains a complete data analytics case study on Netflix movies and TV shows using **Power BI**.  
The project focuses on analyzing content trends, IMDb ratings, runtime patterns, and audience engagement over time through interactive visualizations.

---

## 🔗 Project Resources
- 📁 **Dataset:**  
  https://docs.google.com/spreadsheets/d/1oZSdr3oeHu1Y9bEAc4xneNEBYgWabpyd/edit?usp=sharing

- 📄 **Case Study Report (PDF):**  
  https://drive.google.com/file/d/1CcHsxw7fTSbXWF_DUxYUdUO4aPcr3GFs/view?usp=sharing

---

## 📁 Dataset Summary
- **Total Records:** 5,283
- **Content Types:** Movies and TV Shows
- **Time Period:** 1953 – 2022

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
- Created a custom weighted metric to combine rating quality and popularity:
- Restricted time-based trend analysis to **Movies only** to avoid bias caused by TV shows

---

## 📊 Business Questions Answered
1. Which movies and TV shows perform best based on weighted IMDb ratings?
2. How has the number of movie releases changed over time?
3. How have average IMDb ratings for movies evolved over the last 50 years?
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
- Interactive slicers for:
  - Release Year  
  - Content Type  

Each visualization was designed carefully to avoid misleading interpretations caused by uneven data distribution across years.

---

## 🧠 Key Insights
- Netflix content is heavily skewed toward releases after 2010
- Average IMDb ratings fluctuate over time without a clear long-term trend
- TV shows generally receive higher IMDb ratings than movies
- PG-13 movies and TV-14 shows have the highest average ratings
- Average runtime has become more consistent in recent decades

---

## 🛠 Tools & Technologies Used
- **Power BI Desktop**
- **Power Query Editor**
- **DAX (basic measures)**
- **Excel** (initial data exploration)

---

## 📂 Repository Structure

---

## 🚀 How to Run This Project
1. Clone or download this repository
2. Open `Netflix_Analysis.pbix` using **Power BI Desktop**
3. Use slicers to explore different insights
4. Review the PDF case study for detailed explanations

---

## 📌 Conclusion
This project demonstrates how effective data cleaning, custom metric creation, and thoughtful visualization design can transform raw streaming data into actionable insights. Power BI enables strong data storytelling while highlighting important limitations such as data skewness and missing values.

---

## 👤 Author
**Utkarsh Bansal**  
Aspiring Data Analyst  
GitHub: *(add your GitHub profile link)*  
LinkedIn: *(optional)*

