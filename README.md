# Investigating Netflix Movies (1990s Edition)

This project is a brief exploratory data analysis (EDA) of Netflix's movie catalog from the 1990s. The goal was to examine movie durations and genre trends, focusing on short action films and common runtime patterns. This analysis was conducted as part of a data science learning journey using DataCamp's Datalab environment.

## 🎯 Project Objectives

- Filter the dataset to focus on **1990s movies only**
- Identify the **most common movie duration** during the decade
- Count the number of **short action movies** (less than 90 minutes)

## 🗃️ Dataset Overview

The dataset used in this analysis is [`netflix_data.csv`](./netflix_data.csv) and contains the following columns:

| Column         | Description                        |
|----------------|------------------------------------|
| `show_id`      | Unique ID of the show              |
| `type`         | Type of content (e.g., Movie)      |
| `title`        | Title of the show                  |
| `director`     | Director of the show               |
| `cast`         | Cast members                       |
| `country`      | Country of origin                  |
| `date_added`   | Date added to Netflix              |
| `release_year` | Release year of the content        |
| `duration`     | Duration in minutes                |
| `description`  | Short summary of the content       |
| `genre`        | Genre category                     |

## 🔍 Key Findings

- ✅ The **most frequent movie duration** in the 1990s was **94 minutes**
- 🎬 Only **7 short action movies** (less than 90 minutes) were released during that decade

## 🛠️ Tools Used

- **Python**
- **pandas** for data manipulation

## 📌 How to Use

1. Clone or download this repository
2. Open the notebook [`PROJECT - INVESTIGATING NETFLIX MOVIES.ipynb`](./Investigating_Netflix_Movies.ipynb) in Jupyter or a compatible notebook environment
3. Run the cells to reproduce the analysis
4. Modify filters to explore different decades, genres, or durations

## ✍️ Author

Project by **Achraf Salimi** — part of an ongoing journey to build and showcase data science skills.
