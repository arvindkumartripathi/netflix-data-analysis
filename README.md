# 🎬 Netflix Movies and TV Shows Data Analysis

## 📌 Project Overview

This project focuses on analyzing the Netflix Movies and TV Shows dataset using Python. The main objective is to explore Netflix content, clean the dataset, handle missing values, and visualize useful insights through graphs and charts.

The project uses **Pandas, NumPy, Matplotlib, and Seaborn** for data analysis and visualization.

## 📁 Dataset Source

The dataset used in this project was downloaded from **Kaggle**.

**Dataset Name:** Netflix Movies and TV Shows

**Source:** [Kaggle – Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/ranaghulamnabi/netflix-movies-and-tv-shows-dataset)

## 🎯 Objectives

- Explore the Netflix Movies and TV Shows dataset.
- Identify and remove duplicate records.
- Handle missing values in important columns.
- Convert date columns into proper datetime format.
- Remove unnecessary spaces from text columns.
- Perform Exploratory Data Analysis (EDA).
- Create visualizations to understand Netflix content distribution.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data cleaning and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Google Colab / Jupyter Notebook | Code execution |

## 📂 Project Structure

```text
Netflix-Data-Analysis/
│
├── Arvind_Kumar_Tripathi_2026B01011080.ipynb
│
├── netflix_titles.csv
│
├── netflix_titles_cleaned.csv
│
└── README.md
```

## 📊 Project Workflow

### 1. Data Loading
- Imported the required Python libraries.
- Loaded the Netflix dataset using Pandas.

### 2. Basic Data Exploration
- Displayed the first five records.
- Checked the number of rows and columns.
- Examined column names and data types.
- Identified missing values.
- Generated a statistical summary.

### 3. Data Cleaning
- Identified and removed duplicate records.
- Handled missing values in director, cast, country, date_added, rating, and duration columns.
- Converted the date_added column into datetime format.
- Removed extra spaces from selected text columns.
- Checked the dataset after cleaning.

### 4. Exploratory Data Analysis (EDA)

Performed analysis on:

- Movies vs TV Shows.
- Content release years.
- Top 10 release years.
- Top 10 content ratings.
- Top 10 countries.
- Most common content categories.

### 5. Data Visualization

Created different charts to understand the dataset:

- Bar chart for Movies vs TV Shows.
- Bar chart for Top 10 Release Years.
- Bar chart for Top 10 Ratings.
- Bar chart for Top 10 Countries.
- Pie chart for Movies vs TV Shows distribution.

## 📈 Key Learning Outcomes

Through this project, I learned:

- How to work with real-world datasets.
- How to identify and handle missing values.
- How to remove duplicate records.
- How to perform data cleaning using Pandas.
- How to conduct Exploratory Data Analysis.
- How to create charts and visualizations using Matplotlib.

## ▶️ How to Run This Project

**Step 1:** Clone this repository.

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
```

**Step 2:** Open the project notebook in Google Colab or Jupyter Notebook.

**Step 3:** Upload the `netflix_titles.csv` dataset.

**Step 4:** Run the notebook cells in sequence.

**Step 5:** After execution, the cleaned dataset will be generated as:

```text
netflix_titles_cleaned.csv
```

## 📁 Dataset

Dataset used: Netflix Movies and TV Shows.

The dataset contains information about Netflix titles, including:
- Show ID
- Type
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Listed In
- Description

## 👨‍💻 Author

**Arvind Kumar Tripathi**
<br>
**Btech 1st year**

## ⭐ Conclusion

This project helped me understand the complete process of data analysis, starting from loading raw data to cleaning, exploring, and visualizing meaningful information.

It provided practical experience in using Python libraries for data analysis and improved my understanding of Exploratory Data Analysis (EDA).

---

