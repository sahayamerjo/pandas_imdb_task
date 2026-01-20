# IMDb Movie Data Analysis using Pandas

This project performs exploratory data analysis on IMDb movie data usingPython and Pandas. The dataset contains information about movies, ratings, votes, actors, directors, budget, and gross earnings.
This project analyzes IMDb movie data using Python and Pandas to extract insights on ratings, profitability, voting behavior, and actor popularity.

---

## Dataset
The dataset used in this project is sourced from the  **International Movie Database (IMDb)**.

📂 File: `data/IMDb_movies.csv`

---

##  Objectives
The basic analysis carried out in this project answers the following questions:

1. Which are the highest grossing movies?
2. Which movies have the highest average user vote?
3. Which movies have the most polarised votes?
4. Which movies show the largest vote difference by gender?
5. What is the gross income per director?

---

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Tasks Performed

### 🔹 Task 1: Reading & Inspecting Data
- Imported required libraries
- Loaded IMDb dataset using `read_csv`
- Checked number of rows and columns
- Displayed column information using `info()`
- Generated summary statistics using `describe()`

---

### 🔹 Task 2: Data Analysis
- Converted budget and gross values to million dollars
- Created a profit column
- Identified top 10 profitable movies
- Found movies with losses
- Normalized MetaCritic scores to match IMDb scale
- Calculated average ratings
- Filtered movies based on rating conditions
- Identified most popular actor trios using Facebook likes
- Extracted top 10 movies based on CVotesU18
