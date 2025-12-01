# Netflix Dataset Analysis - README

## 📌 Overview

This project analyzes a Netflix dataset using Python. It includes data loading, cleaning, exploration, and visualization to uncover insights about the content available on Netflix.

## 📂 Dataset

The dataset includes:

* Title information
* Content type (Movie/TV Show)
* Release year
* Date added to Netflix
* Rating
* Duration
* Genre and cast
* Country of origin

## 🛠️ Tools & Libraries Used

* **Pandas** for data manipulation
* **NumPy** for numerical operations
* **Matplotlib / Seaborn** for visualizations
* **Jupyter Notebook** as the development environment

## 🧹 Data Cleaning Steps

* Checked dataset shape and structure (`info()`, `describe()`)
* Detected and counted missing values
* Filled missing numerical fields with **0** when applicable
* Handled categorical missing data depending on column meaning
* Removed duplicate entries using `duplicated().sum()`

## 🔍 Exploratory Data Analysis (EDA)

The analysis includes:

* Distribution of movies vs TV shows
* Popular content ratings
* Content added over the years
* Duration analysis
* Genre and country breakdown
* Detection of outliers and trends

## 📊 Visualizations

Several plots were created to understand data patterns:

* Count plots
* Histograms
* Bar charts
* Correlation heatmaps

## 📈 Insights & Findings

* Overview of missing data impact
* Trend of Netflix adding more content in recent years
* Most common ratings across platform
* Movie durations vs TV show seasons
* Countries dominating Netflix content

## 📝 Project Structure

```
netflix-analysis/
│── netflix.ipynb        # Main analysis notebook
│── Netflix Data new.csv # Dataset used
│── README.md            # This file
```

## ▶️ How to Run the Notebook

1. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

2. Open Jupyter Notebook:

```bash
jupyter notebook
```

3. Run all cells in `netflix.ipynb`.
