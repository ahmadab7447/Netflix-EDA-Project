
---

# 📊 Netflix Exploratory Data Analysis (EDA)

This project performs an Exploratory Data Analysis on the Netflix dataset to uncover insights and trends in its content offerings. The analysis includes data cleaning, visualization, and exploration of various features such as release year, genre distribution, content type, and more.

## 📁 Dataset

* **Source**: [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
* **Attributes include**:

  * Title
  * Director
  * Cast
  * Country
  * Date added
  * Release year
  * Rating
  * Duration
  * Genre (listed as “Category”)
  * Description

## 📌 Objectives

* Understand the structure and content of the dataset.
* Clean and preprocess the data.
* Explore distribution of shows over time and by category.
* Visualize content trends by country, year, rating, and type.
* Derive insights using visual tools like seaborn and matplotlib.

## 📈 Key Findings

* Majority of the content added is post-2015.
* The United States contributes the most content.
* TV Shows are slightly more than Movies in the dataset.
* Most common rating for Movies is ‘TV-MA’, and for TV Shows it's ‘TV-14’.
* 2019 had the highest number of content additions.

## 🧰 Tools and Libraries

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

## 📊 Visualizations

* Count plots for content type and ratings
* Bar plots for top contributing countries
* Heatmaps to identify correlations
* Time series analysis of content addition by year

## 🛠️ How to Run

1. Clone the repository or download the notebook.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the Jupyter Notebook and run the cells.

## 📎 File Structure

```
Netflix-EDA_PROJECT/
├── analysis.ipynb     # Jupyter notebook containing the complete analysis
└── README.md          # Project documentation
└── requirements.txt       # Libraries

---







