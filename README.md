# Pandas Challenge: 100 Netflix Practice Questions

Welcome to my Python Pandas project! In this repository, I solve **100 practical questions** using a real Netflix dataset (`netflix_titles.csv`). 

This project shows how I went from writing basic Pandas code to building advanced, fast, and optimized data workflows.

---

## About the Dataset
The dataset we are using is named `netflix_titles.csv`. It contains information about movies and TV shows on Netflix, including:
* **Title & Type:** The name of the movie/show and whether it is a "Movie" or a "TV Show".
* **People involved:** Directors and cast members.
* **Release Info:** The country it was made in, the year it came out, and the date it was added to Netflix.
* **Details:** The maturity rating, the duration (in minutes or seasons), and a short description.

---

## The 4 Learning Phases

The notebook is split into 4 levels that get progressively more challenging:

### Phase 1: Beginner Level Foundations (Q1 - Q25)
* Learning how to load data and look at rows and columns.
* Selecting specific columns, sorting data, and removing columns we don't need.
* Basic filtering (like showing *only* Movies).

### Phase 2: Intermediate Data Wrangling (Q26 - Q60)
* Filtering with multiple rules (like finding Movies made in India in 2021).
* Handling missing or blank data cleanly.
* Fixing text data (like separating numbers from text in the duration column, e.g., turning `"90 min"` into `90`).
* Grouping data to find averages and counts.

### Phase 3: Advanced Transformations (Q61 - Q80)
* Breaking down lists separated by commas (like finding out which actors appear the most).
* Creating advanced summary tables (Pivot Tables and Crosstabs).
* Saving computer memory by changing how data is stored.

### Phase 4: Pro-Level Optimization & Pipelines (Q81 - Q100)
* Building clean "data pipelines" where multiple steps happen in one go.
* Dealing with complex indexing.
* Proving why native Pandas code runs **100x faster** than using standard Python `for` loops.

---

## 📂 Project Structure
```text
├── data/
│   └── netflix_titles.csv          # The raw data file
├── notebooks/
│   └── pandas_mastery_challenge.ipynb # My Jupyter Notebook with questions & code
└── README.md                       # This file!
