# netflix-movie-data-wrangling

# Movie Data Wrangling and Analysis Project

## 📁 Project Overview

This project demonstrates real-world data wrangling and analysis using two movie-related datasets. It simulates challenges analysts face when working with raw, messy data, and showcases techniques to clean and prepare data for meaningful insights.

---

## 📌 Project Goal

The goal is to compare movies listed on Netflix with a broader movie dataset that includes various attributes such as budget, revenue, and ratings. By cleaning and merging these datasets, the analysis aims to uncover interesting insights about movies available on Netflix versus the general market.

---

## 🗂️ Datasets Used

1. **Movie Metadata Dataset**  
   - Contains detailed information about movies including budget, revenue, release dates, popularity, and user ratings.

2. **Netflix Movies and TV Shows Dataset**  
   - Contains titles available on Netflix, along with their release year, type, and other attributes.

---

## 🔧 Project Workflow

### 1. Data Gathering
- Downloaded and imported two datasets:
  - `movies_metadata.csv`
  - `netflix_titles.csv`

### 2. Data Assessment
- Assessed both datasets visually and programmatically to identify:
  - Missing values
  - Incorrect data types
  - Duplicates
  - Inconsistencies

### 3. Data Cleaning
- Addressed missing and null values
- Converted data types where needed (e.g., budget and revenue fields)
- Removed duplicates
- Standardized and normalized relevant fields (e.g., movie titles for joining datasets)

### 4. Data Merging
- Cleaned datasets were merged using movie titles and release years as keys.
- A final clean dataset was created for analysis purposes.

---

## 📊 Key Analyses

The merged dataset enabled various analyses such as:

- **Top Grossing Netflix Movies:** Identified high-revenue movies available on Netflix.
- **Netflix vs General Ratings:** Compared IMDb and user ratings between Netflix and non-Netflix movies.
- **Revenue and Budget Trends:** Analyzed how budget correlates with revenue across the two datasets.
- **Release Trends:** Examined how the number of movie releases varies by year and platform.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

## 📈 Visualizations

The notebook includes a variety of visualizations including:

- Bar plots comparing top-rated and top-grossing Netflix movies
- Scatter plots for budget vs revenue
- Distribution plots of ratings
- Time series plots of movie releases

---

## 🔚 Conclusion

This project highlights the critical importance of data wrangling in real-world analysis. Despite messy and imperfect data, proper cleaning and joining methods make it possible to derive meaningful business insights.

---

## 📎 File Structure

