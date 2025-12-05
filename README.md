# YouTube Trending Data Analysis

Youtube_Data_Project
/Cover_picture.png


## Foundations of Computer Science — Final Project
### University of Milano – Bicocca, MSc in Data Science

This project was developed as the final assignment for the Foundations of Computer Science course within the MSc in Data Science program at University of Milano – Bicocca.

The work is collaboratively carried out by:
- **Güldeniz Güzelay**
- **Sude Aslan**
- **Tony Dawra**

- ---

## Project Description

This project analyzes YouTube trending video datasets from **10 different countries**:

- `CA` — **Canada**  
- `DE` — **Germany**  
- `FR` — **France**  
- `GB` — **United Kingdom**  
- `IN` — **India**  
- `JP` — **Japan**  
- `KR` — **South Korea**  
- `MX` — **Mexico**  
- `RU` — **Russia**  
- `US` — **United States**

Each dataset is provided in CSV format and contains the following variables:
- video_id  
- trending_date  
- title  
- channel_title  
- category_id  
- publish_time  
- tags  
- views  
- likes  
- dislikes  
- comment_count  
- thumbnail_link  
- comments_disabled  
- ratings_disabled  
- video_error_or_removed  
- description  
- country  
- like_ratio  
- publish_time_round  
- publish_interval_10m  
- trending_datetime  
- trend_year  
- trend_month  
- trend_day

  ---

## 🎯 Project Objectives

The project answers the following **15 analytical questions**:

1. Concatenate all CSV files into a single dataframe and add a `country` column.  
2. Extract all videos that have **no tags**.  
3. For each channel, compute the **total number of views**.  
4. Save rows with **disabled comments**, **disabled ratings**, or **video errors** into a dataframe named `excluded`, and remove them from the main dataset.  
5. Add a `like_ratio` column (likes/dislikes).  
6. Cluster `publish_time` into **10-minute intervals**.  
7. For each interval, compute:  
   - number of videos  
   - average number of likes  
   - average number of dislikes  
8. For each tag, compute the **number of videos** containing that tag.  
9. Identify the tags with the **highest number of videos**.  
10. For each `(tag, country)` pair, compute the **average like/dislike ratio**.  
11. For each `(trending_date, country)` pair, find the video with the **most views**.  
12. Split `trending_date` into **year, month, day**.  
13. For each `(month, country)` pair, find the video with the **most views**.  
14. Read all category JSON files.  
15. For each country, determine how many videos belong to a **non-assignable category**.

---

## 👥 Authors & LinkedIn Profiles

| Name | LinkedIn |
|------|----------|
| **Güldeniz Güzelay** | <a href="https://www.linkedin.com/in/guldenizguzelay/" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="26"/></a> |
| **Sude Aslan** | <a href="https://www.linkedin.com/in/sude-aslan/" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="26"/></a> |
| **Tony Dawra** | <a href="https://www.linkedin.com/in/tony-dawra-232218292/" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="26"/></a> |

---

