# Netflix Movies & TV Shows — Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a Netflix Movies and TV Shows dataset.

The goal is to understand the content available in the dataset and identify patterns related to content type, release years, ratings, movie duration, TV show seasons, genres, countries, directors, actors, and content added over time.

This project was created using Python and common data analysis libraries.

---

## Objectives

The main objectives of this project are:

- Understand the structure of the Netflix dataset
- Analyze Movies vs TV Shows
- Identify missing values
- Analyze content by release year
- Explore Netflix content ratings
- Analyze movie durations
- Analyze the number of seasons in TV Shows
- Identify the most common genres
- Analyze countries represented in the dataset
- Analyze content added to Netflix over time
- Identify directors with the most titles
- Identify actors appearing across multiple titles
- Extract useful insights from the data

---

## Dataset

The dataset used in this project is the **Netflix Movies and TV Shows** dataset from Kaggle.

Dataset source:

https://www.kaggle.com/shivamb/netflix-shows

The dataset contains **8,807 titles** and **12 columns**.

### Main Columns

| Column | Description |
|---|---|
| `show_id` | Unique ID of the title |
| `type` | Movie or TV Show |
| `title` | Title of the content |
| `director` | Director of the title |
| `cast` | Actors appearing in the title |
| `country` | Country or countries associated with the title |
| `date_added` | Date the title was added |
| `release_year` | Original release year |
| `rating` | Content rating |
| `duration` | Movie duration or number of seasons |
| `listed_in` | Genres/categories |
| `description` | Description of the title |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

Loaded the Netflix dataset using Pandas and examined its basic structure.

### 2. Data Exploration

Checked:

- Number of rows and columns
- Column names
- Data types
- Basic statistics
- Missing values

### 3. Data Cleaning

Handled missing values and corrected inconsistent data in the `rating` and `duration` columns.

The `date_added` column was also converted from text into a datetime format for time-based analysis.

### 4. Exploratory Data Analysis

The project analyzes:

- Movies vs TV Shows
- Release year distribution
- Content ratings
- Movie durations
- TV Show seasons
- Genres
- Countries
- Content added by year
- Directors
- Actors

---

## Key Findings

### Movies vs TV Shows

The dataset contains:

- **6,131 Movies**
- **2,676 TV Shows**

Movies represent approximately **69.6%** of the dataset.

### Content Added Over Time

The number of titles added increased significantly after 2016.

The dataset contains the highest number of additions in **2019**, with **2,016 titles**.

### Content Ratings

The most common ratings include:

- TV-MA
- TV-14
- TV-PG
- R

TV-MA is the most common rating in the dataset.

### Movie Duration

The average movie duration is approximately **99.6 minutes**, while the median duration is **98 minutes**.

Most movies are concentrated around the 80–120 minute range.

### TV Show Seasons

TV Shows with **1 season** are the most common in the dataset.

### Popular Genres

Some of the most frequently occurring categories include:

- International Movies
- Dramas
- Comedies
- International TV Shows
- Documentaries

### Countries

The United States has the highest number of titles associated with it, followed by India and the United Kingdom.

### Directors

Some directors appear across many titles. Rajiv Chilaka has the highest number of titles among the directors in this dataset, with **19 titles**.

### Actors

Anupam Kher appears in the highest number of titles among the actors analyzed, with **43 titles**.

---

## Visualizations

The project includes visualizations for:

- Movies vs TV Shows
- Titles by release year
- Movies vs TV Shows by release year
- Content ratings
- Movie duration distribution
- Number of seasons in TV Shows
- Top genres
- Top countries
- Titles added by year
- Movies vs TV Shows added by year
- Top directors
- Top actors

---

## Project Structure

```text
Netflix-EDA/
│
├── netflix_titles.csv
├── Netflix_EDA.ipynb
└── README.md