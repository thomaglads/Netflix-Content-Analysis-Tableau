# Netflix-Content-Analysis-Tableau
A comprehensive analysis of the Netflix content library using Tableau, featuring two distinct dashboards: a Content Library Overview and a deep dive into Content Strategy.

# Comprehensive Netflix Content Analysis in Tableau

## Project Objective
This project performs a comprehensive analysis of the Netflix content library using Tableau. The goal was to create two distinct, interactive dashboards to answer different business questions: one providing a high-level overview of the content available, and a second dashboard offering a deeper analysis of Netflix's content strategy over time.

---

## Dashboard 1: Netflix Content Library Overview
This dashboard provides a summary of the Netflix library, answering foundational questions about its composition and growth.

Content Library Overview Screenshot
![WhatsApp Image 2025-06-10 at 23 28 14_318bc77e](https://github.com/user-attachments/assets/f53101c5-6f6d-43fc-bdf8-851fb03dc5dc)


**Key Insights from this Dashboard:**
* **Content Mix:** The library is predominantly composed of Movies, making up the majority of the titles compared to TV Shows.
* **Content Growth:** There was an exponential increase in content added to the platform, peaking sharply between 2016 and 2020.
* **Geographic Reach:** While the United States is the largest single producer of content, India and the United Kingdom follow as significant contributors.
* **Top Genres:** Dramas, International Movies, and Documentaries are among the most frequent primary genres available on the platform.

---

## Dashboard 2: Netflix Content Strategy: An Analysis of Ratings & Runtimes
This dashboard explores the strategic decisions behind the content, focusing on target audience (maturity ratings) and content format (duration).

Content Strategy Screenshot
![image](https://github.com/user-attachments/assets/5f3a3d2a-34c6-40bc-bad1-d8df21656eae)


**Key Insights from this Dashboard:**
* **Target Audience:** The content library is heavily skewed towards mature audiences, with **TV-MA** being the most common maturity rating, followed by **TV-14** and **R**.
* **Evolving Strategy:** The "Evolution of Content Strategy" chart shows a clear shift over time. The proportion of content rated TV-MA (for mature audiences) has significantly increased in recent years, indicating a strategic focus on adult viewers.
* **Content Format (Movies):** The "Distribution of Movie Runtimes" histogram shows that the vast majority of movies on Netflix cluster around the standard **85-120 minute** mark.
* **Content Format (TV Shows):** The "Distribution of TV Show Seasons" chart reveals a key part of Netflix's strategy: a very large number of TV shows only last for **1 Season**.

## Data Source
The analysis was performed on the "Netflix Movies and TV Shows" dataset, a popular and well-structured dataset sourced from Kaggle.

## Tools & Techniques
* **Tableau Desktop:** Used for the entire workflow, from data preparation to creating all visualizations and assembling the final interactive dashboards.
* **Data Preparation:** Handled data quality issues within Tableau, including:
    * Converting `date_added` from text to a Date type.
    * Parsing the `duration` field into separate numerical measures for movie minutes and TV show seasons using calculated fields.
    * Splitting the multi-value `listed_in` (genre) column to analyze by primary genre.
    * Filtering out erroneous data from the `rating` column.
* **Advanced Visualization:**
    * Created a **100% Stacked Bar Chart** using table calculations (`Percent of Total`) to analyze the proportional shift in content strategy over time.
    * Built a **Histogram** to analyze the distribution of movie runtimes.

## Skills Demonstrated
* Data Visualization & Dashboard Design (Tableau)
* Data Cleaning and Preparation
* Calculated Field Creation
* Table Calculations (`Percent of Total`)
* Strategic & Exploratory Data Analysis
* Telling multiple, distinct stories from a single dataset.
