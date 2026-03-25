# Netflix Content Analysis Project (SQL)

Analyzed the Netflix Movies and TV Shows dataset using SQL to understand content growth, content mix, and regional trends over time. Performed data cleaning, exploratory analysis, and advanced SQL queries using CTEs and window functions to uncover insights on genres, durations, ratings, and country-wise distribution. Delivered business insights on Netflix’s content strategy, growth patterns, and audience engagement drivers.

## 📌 Project Overview

This project uses the Netflix Titles dataset, which contains thousands of rows of information about Movies and TV Shows available on Netflix.

The dataset includes:

- Show ID
- Title
- Content Type
- Director
- Cast
- Country
- Date Added to Netflix
- Release Year
- Rating
- Duration
- Genre (`listed_in`)
- Description

It is well suited for:

- Exploratory Data Analysis
- Content growth analysis
- Content mix analysis
- Regional trend analysis
- Audience preference insights
- KPI creation using SQL

## 🧠 Business Problem

The main objective of this project was to understand Netflix’s content strategy and growth patterns over time.

As a global streaming platform, Netflix needs data-driven insights to evaluate:

- How quickly its content library is growing
- Whether it is focusing more on Movies or TV Shows
- Which countries, genres, and ratings dominate the platform
- How content duration and TV show seasons vary over time
- How new vs old content contributes to growth

## 🎯 Analysis Questions Answered

This project answers 25+ real business questions, including:

- How many titles are added each year on Netflix?
- What is the percentage split between Movies and TV Shows?
- Which countries produce the most Netflix content?
- What is the average movie duration and TV show seasons?
- Which movies have the longest runtime?
- Who are the top actors appearing in Indian movies?
- What is the Year-over-Year growth of content?
- What is the Month-over-Month growth of content?
- How is content distributed by country, genre, rating, and content type?
- How do duration trends change over time?
- What is the split between old and new content?
- Which months show the highest content additions?
- Which actors and directors appear most frequently in key regions?

## 🛠️ Tools and Technologies Used

- Microsoft SQL Server
- SQL Queries for Data Cleaning and Analysis
- CTEs
- Window Functions (`LAG`, `AVG OVER`)
- Aggregate Functions (`COUNT`, `AVG`, `ROUND`)
- String Functions (`LTRIM`, `RTRIM`, `CHARINDEX`)
- `CASE` Statements
- Self Joins

## 🧹 Data Cleaning

The dataset was cleaned by:

- Handling `NULL`, blank, and `"Not Given"` values
- Standardizing duration fields into numeric values
- Extracting year and month from the `date_added` column
- Filling missing director values using self-joins
- Checking for duplicates and invalid rows

## 📊 Exploratory Data Analysis

Performed EDA to understand:

- Total number of rows and columns
- Null value distribution
- Duplicate records
- Content type distribution
- Country-wise and genre-wise trends
- Rating distribution
- Duration patterns

## 🔍 Advanced SQL Concepts Used

- CTEs for modular and readable queries
- Window Functions for YoY and MoM analysis
- Aggregation for KPI calculations
- String Manipulation for cleaning and parsing values
- CASE Logic for content classification
- Bucketing for runtime and seasons

## 📈 Key Insights

- Netflix’s content growth accelerated significantly after 2016, peaking during 2019–2020
- Movies make up the majority of the catalog, while TV Shows contribute to longer engagement
- The United States and India are the top content-producing countries
- Most movies fall within the 90–120 minute duration range
- Netflix adds more new content than old content, especially in recent years
- Certain actors and directors appear repeatedly, showing reliance on proven talent
- Average movie duration has gradually increased over time
- TV shows typically range between 1–3 seasons, with a few long-running exceptions

## 💡 Recommendations

- Continue strategies from high-growth years like 2018–2019
- Invest in TV Shows to improve long-term engagement
- Focus on countries that consistently perform well
- Plan content releases around high-performing months
- Use content duration trends to align with audience preference


---

## 👤 Author

**Moksh Kapoor**  
Aspiring Data Analyst  

<p>
  🔗 <strong>LinkedIn:</strong> 
  <a href="https://www.linkedin.com/in/moksh-kapoor-618495322/" target="_blank" style="text-decoration:none; color:#0A66C2; font-weight:bold;">
    Visit My LinkedIn Profile
  </a>
</p>

📢 You can also check this project on my LinkedIn post: 
<a href="https://www.linkedin.com/posts/moksh-kapoor-618495322_dataanalytics-dataanalysis-excel-activity-7438566531006894080-w_mV?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFGVzjQBQzKnpNzkuOZayyyvYW4FkHnrf28" target="_blank">
View Post 🚀
</a>

If you like this project, ⭐ **give it a star** on GitHub to show your support!

