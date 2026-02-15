# Netflix_Analysis
## 📊 Netflix Movies & TV Shows — Exploratory Data Analysis

This project performs an in-depth exploratory data analysis (EDA) of the Netflix Titles dataset to uncover patterns, trends, and insights about movies and TV shows available on the platform. The analysis focuses on content distribution, release patterns, ratings, duration, and geographical production.

The dataset was cleaned by handling missing values, converting data types, and preparing features for analysis. Visualizations were created to better understand Netflix’s content strategy and how it has evolved over time.

---

## 🎯 Objectives

* Analyze the distribution of Movies vs TV Shows
* Examine content release trends across years
* Explore ratings and duration patterns
* Identify top contributing countries
* Handle missing data effectively
* Generate meaningful insights from real-world data

---

## 🧹 Data Preprocessing

The dataset required several cleaning steps before analysis:

* Handling missing values in columns such as director, cast, and country
* Converting date fields into proper datetime format
* Standardizing categorical values
* Creating additional features for analysis

---

## 📈 Key Insights

* Movies dominate Netflix’s content library compared to TV Shows
* Significant growth in content additions occurred after 2015
* A few countries contribute the majority of content
* Content ratings vary significantly between Movies and TV Shows
* Most titles fall within specific duration ranges

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Project Structure

```
netflix-analysis/
│
├── Netflix_EDA.ipynb      # Main analysis notebook
├── netflix_titles.csv     # Dataset
├── images/                # Saved visualizations
├── requirements.txt       # Required Python libraries
└── README.md              # Project documentation
```

---

## 📊 Dataset

Netflix Titles Dataset containing information about movies and TV shows such as title, director, cast, country, release year, rating, and duration.

---

## ▶️ How to Run This Project

1️⃣ Clone the repository

```
git clone <your-repo-link>
```

2️⃣ Install dependencies

```
pip install -r requirements.txt
```

3️⃣ Launch Jupyter Notebook

```
jupyter notebook
```

4️⃣ Open `Netflix_EDA.ipynb` and run all cells

---

## 🎯 Skills Demonstrated

* Data Cleaning & Preprocessing
* Handling Missing Values
* Exploratory Data Analysis (EDA)
* Data Visualization
* Insight Extraction
* Working with Real-World Dataset

---

## 🚀 Future Improvements

* Build a recommendation system
* Perform genre-based analysis
* Apply machine learning models
* Create interactive dashboards