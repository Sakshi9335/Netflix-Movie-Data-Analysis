
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg" alt="Netflix Logo" height="120">
</p>

<h1 align="center">📊 Netflix Movie Data Analysis</h1>

<p align="center">
  A data analysis project that explores, cleans, and visualizes Netflix movie dataset to uncover trends and insights.
</p>

---

## 📂 Project Structure

```

Netflix-Movie-Data-Analysis/
│
├── movie data analysis netflix.ipynb   # jupyter notebook
├── mymoviedb.xls                       # dataset
└── resources ppt.pdf                   # presentation

````

---

## 🧠 Overview

This project performs exploratory data analysis (EDA) on a dataset of Netflix movies.  
The main objectives are:

- Data cleaning and preprocessing
- Date and time formatting for analysis
- Category-wise segmentation
- Visualization of trends in genres, release years, and ratings

---

## 📌 Dataset Highlights

- **Format:** Excel (`.xls`)
- **Columns:** Movie title, release date, popularity, genres, vote average, language, etc.
- **Data Cleaning:**  
  - Removed duplicates  
  - Converted date fields to datetime  
  - Grouped genres into broader categories
- **Outliers:** Checked and handled for numerical columns

---

## 📊 Key Visual Insights

- 📈 Rise in movie releases after **2010**
- 🎭 Popular genres include **Drama**, **Action**, and **Comedy**
- 🌐 Majority of movies are in **English**
- 🔥 Popularity column has noticeable outliers
- ⭐ Most movies have an average rating between **6–8**

---

## 🚀 How to Run the Project

### 1. Install Required Libraries:
```bash
pip install pandas matplotlib seaborn openpyxl
````

### 2. Launch Jupyter Notebook:

```bash
jupyter notebook "movie data analysis netflix.ipynb"
```

---

## 📥 Data Source

The dataset is stored locally as `mymoviedb.xls` and contains movie-level information such as:

* Title
* Release Date
* Popularity
* Genres
* Vote Average
* Language

---

## 🎓 Tools & Technologies Used

* **Python** (Pandas, Matplotlib, Seaborn)
* **Jupyter Notebook**
* **Excel Dataset**
* **Data Cleaning & Feature Engineering**
* **Visualization for Insights**

---

## 📽️ Output Formats

* ✅ Jupyter Notebook (`.ipynb`)
* ✅ PDF Presentation (`resources ppt.pdf`)

---

> Made with ❤️ for data science and Netflix movie fans.

````
