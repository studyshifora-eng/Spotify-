#  Spotify SQL Data Analysis Project


![Spotify Logo](https://github.com/najirh/najirh-Spotify-Data-Analysis-using-SQL/blob/main/spotify_logo.jpg)

## 📌 Project Overview

This project focuses on analyzing Spotify music data using SQL to extract meaningful insights about tracks, artists, albums, streaming performance, and audio characteristics.

The analysis includes basic to advanced SQL queries to explore music trends, compare streaming platforms, identify top-performing tracks, and understand song attributes such as energy, danceability, and liveness.

## 🎯 Project Objectives

- Analyze track and artist performance.
- Identify tracks with high streaming numbers.
- Explore album and artist relationships.
- Compare Spotify and YouTube streaming performance.
- Analyze audio features such as energy and danceability.
- Practice advanced SQL concepts, including CTEs and window functions.

## 🗂️ Dataset Description

The dataset contains information about Spotify tracks, artists, albums, audio features, and engagement metrics.

### Key Columns

| Column | Description |
|---|---|
| Artist | Name of the artist |
| Track | Name of the track |
| Album | Album name |
| Album Type | Type of album (single, album, etc.) |
| Danceability | Danceability score of the track |
| Energy | Energy level of the track |
| Loudness | Loudness of the track |
| Acousticness | Acousticness score |
| Liveness | Liveness score |
| Tempo | Tempo of the track |
| Views | Total video views |
| Likes | Number of likes |
| Comments | Number of comments |
| Stream | Streaming count |
| Most Played On | Platform where the track is most played |

## 🛠️ Tools & Technologies

- **SQL**
- PostgreSQL-compatible SQL syntax
- GitHub

## 🔍 SQL Concepts Used

This project demonstrates the following SQL concepts:

- SELECT and WHERE statements
- DISTINCT
- Aggregate Functions (SUM, COUNT, AVG, MAX, MIN)
- GROUP BY and ORDER BY
- LIMIT
- CASE WHEN
- COALESCE
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- DENSE_RANK()
- Data filtering and comparison

## 📊 Analysis Performed

The project includes SQL queries to answer the following questions:

1. Retrieve tracks with more than 1 billion streams.
2. List albums and their respective artists.
3. Calculate total comments for licensed tracks.
4. Identify tracks belonging to the single album type.
5. Count the total number of tracks by each artist.
6. Calculate average danceability for each album.
7. Find the top 5 tracks with the highest energy values.
8. Identify top tracks by views and likes for official videos.
9. Calculate total views for tracks across albums.
10. Compare Spotify and YouTube streaming performance.
11. Find the top 3 most-viewed tracks for each artist using window functions.
12. Identify tracks with above-average liveness scores.
13. Calculate the difference between the highest and lowest energy values for each album using a CTE.

## 💡 Key Learning Outcomes

Through this project, I strengthened my understanding of SQL for data analysis, including:

- Data aggregation and grouping.
- Extracting insights from music datasets.
- Comparing performance metrics across platforms.
- Applying window functions to rank data.
- Using CTEs and subqueries to solve analytical problems.
- Writing structured and readable SQL queries.

## 🚀 Future Improvements

- Create interactive dashboards using Excel or Power BI.
- Perform deeper analysis of artist and track performance.
- Identify trends in audio features and streaming popularity.
- Improve query optimization and data cleaning.
- Develop additional business-oriented insights from the dataset.

## 📁 Project Structure

```text
Spotify-SQL-Project/
│
├── spotify.sql
└── README.md
```

## 👩‍💻 Author

**Shifora Limbu**

Aspiring Data Analyst | SQL | Excel | Data Visualization

---

⭐ If you find this project useful, feel free to explore the SQL queries and insights.
