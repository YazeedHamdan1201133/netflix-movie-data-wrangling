# netflix-movie-data-wrangling

## 📁 Project Overview

This project demonstrates real-world data wrangling and analysis using two movie-related datasets. It simulates challenges analysts face when working with raw, messy data, and showcases techniques to clean and prepare data for meaningful insights.

Author: **Yazeed Hamdan**  
Project: **DA_Project2 - Second Project**

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

This step involved collecting the two primary datasets used in the project:

#### 📦 Movie Metadata Dataset
- **Source**: Kaggle  
- **Access Method**: Kaggle API  
After downloading, it was unzipped and the file `movies_metadata.csv` was extracted and loaded using `pandas.read_csv()`.

## 📺 Netflix Titles Dataset

- **Source**: Local file (assumed to be manually downloaded or provided)  
- **Access Method**: Direct read from CSV using `pandas.read_csv()`

## 🗃️ File Handling Notes

- The working directory was explicitly set to access the files.
- After loading the movie metadata, a raw copy was saved as `raw_movies_metadata.csv` to preserve the original version before cleaning.
- The Netflix dataset (`netflix_titles.csv`) was read and displayed for preview.

This structured and repeatable gathering approach ensures transparency and reproducibility for future work.

---

## 2. Data Assessment

Assessed both datasets visually and programmatically to identify:

- Missing values  
- Incorrect data types  
- Duplicates  
- Inconsistencies  

---

## 3. Data Cleaning

- Addressed missing and null values  
- Converted data types where needed (e.g., budget and revenue fields)  
- Removed duplicates  
- Standardized and normalized relevant fields (e.g., movie titles for joining datasets)  

---

## 4. Data Merging

- Cleaned datasets were merged using movie titles and release years as keys.  
- A final clean dataset was created for analysis purposes.  

---

## 📊 Key Analyses

The merged dataset enabled various analyses such as:

- **Top Grossing Netflix Movies**: Identified high-revenue movies available on Netflix.  
- **Netflix vs General Ratings**: Compared IMDb and user ratings between Netflix and non-Netflix movies.  
- **Revenue and Budget Trends**: Analyzed how budget correlates with revenue across the two datasets.  
- **Release Trends**: Examined how the number of movie releases varies by year and platform.  

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
## 👨‍💻 Authors
This project was developed by:
- **Yazeed Hamdan**
  
---

## 📫 Contact
For any questions or discussions, feel free to reach out:

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yazedyazedl2020@gmail.com)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/yazeed-hamdan-59b83b281/)  


