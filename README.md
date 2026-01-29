# Exploratory Data Analysis (EDA)

This repository contains Exploratory Data Analysis (EDA) performed on two datasets:

1. Netflix Movies and TV Shows Dataset
2. Iris Dataset

The objective of this EDA is to understand the structure of the data, analyze distributions, detect outliers, study relationships between features, and identify important attributes useful for prediction.

---

## 1. Netflix Movies and TV Shows Dataset

### 📌 Dataset Description

The Netflix Movies and TV Shows dataset contains information about movies and TV shows available on Netflix. It includes details such as title, type of content, country, release year, rating, duration, and genre.

### 📊 Key Attributes

* type: Movie or TV Show
* title: Name of the content
* director: Director of the content
* cast: Cast involved
* country: Country of production
* release_year: Year of release
* rating: Content rating (e.g., PG, TV-MA)
* duration: Duration in minutes or seasons
* listed_in: Genre/category

### 🔍 EDA Steps Performed

* Analyzed distribution of release year using histograms
* Visualized categorical variables like content type and ratings using count plots
* Identified outliers in release year using box plots
* Generated correlation heatmap for numerical features

### 📈 Key Insights

* Movies dominate the Netflix catalog compared to TV Shows
* Majority of content was released after 2010
* TV Shows generally have more recent release years than Movies
* Dataset contains mostly categorical features

### 🎯 Important Features for Prediction

* type
* rating
* release_year
* country
* duration

---

## 2. Iris Dataset

### 📌 Dataset Description

The Iris dataset is a classic dataset used in machine learning and statistics. It consists of measurements of iris flowers from three different species.

### 📊 Key Attributes

* sepal length (cm)
* sepal width (cm)
* petal length (cm)
* petal width (cm)
* species: Setosa, Versicolor, Virginica

### 🔍 EDA Steps Performed

* Plotted histograms for all numerical features
* Analyzed species distribution using count plots
* Detected outliers using box plots
* Studied feature relationships using correlation heatmap and pair plots

### 📈 Key Insights

* Petal length and petal width show strong positive correlation
* Setosa species is clearly separable from others
* Versicolor and Virginica show some overlap
* Dataset is clean with no missing values

### 🎯 Important Features for Prediction

* petal length
* petal width
* sepal length

---

## 🛠 Tools & Libraries Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## ✅ Conclusion

The Netflix dataset is suitable for content analysis and recommendation-based studies, while the Iris dataset is ideal for practicing classification algorithms. EDA helped uncover data patterns, relationships, and important features necessary for effective modeling.
