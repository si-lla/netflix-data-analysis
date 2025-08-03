# 🎬 Netflix Data Analysis Project  
**Internship Project at Unified Mentor Private Limited**

This project explores Netflix’s dataset using **Python for EDA and ML**, and **Power BI** for business dashboards.  
It was completed as part of my internship at **Unified Mentor Pvt Ltd**.

---

## 📁 Project Structure

netflix_project/
├── data/ # Raw and processed datasets
├── analysis/ # Jupyter Notebook and cleaned files
├── eda_screenshots/ # EDA output images
├── dashboards/ # Dashboard screenshots (Power BI)
├── netflix_dashboard.pbix # Power BI dashboard file

---

## 📌 Goals of the Project

- Clean Netflix dataset and explore its structure
- Analyze content distribution by type, genre, rating, country, and time
- Build a **genre-based recommendation system using NLP**
- Visualize all insights using interactive dashboards in Power BI

---

## 🧪 Exploratory Data Analysis (Python)

Performed using `pandas`, `matplotlib`, `seaborn`, `collections`, and basic NLP.

| Plot | Description |
|------|-------------|
| ![](eda_screenshots/plot1.png) | Content Type Distribution |
| ![](eda_screenshots/plot2.png) | Content Added Over Time |
| ![](eda_screenshots/plot3.png) | Top Countries |
| ![](eda_screenshots/plot4.png) | Top Genres |
| ![](eda_screenshots/plot5.png) | Rating Breakdown |
| ![](eda_screenshots/plot6.png) | Word Frequency (Title Words) |
| ![](eda_screenshots/plot7.png) | Duration Analysis |

📝 Full EDA and machine learning implementation is in [**netflix_analysis.ipynb**](analysis/netflix_analysis.ipynb)

---

## 🧠 Machine Learning
This project includes two machine learning components:

🔍 1. Genre-Based Recommendation System (NLP)
✅ Built a content-based recommender using Natural Language Processing

✅ Used TF-IDF Vectorization and Cosine Similarity

✅ Returns top 5 similar shows for any given Netflix title

✅ Example:
Input: Stranger Things
Recommendations: Nightflyers, Manifest, The OA, etc.

🎯 2. Supervised Learning – Content Type Classification
✅ Built a Classification Model using Logistic Regression

✅ Target Variable: type (Movie or TV Show)

✅ Input Features: release_year, rating, duration, listed_in, etc.

✅ Evaluated using accuracy score and confusion matrix

✅ Helped understand what factors determine whether content is released as a Movie or a TV Show

📂 Code Location:
 Full EDA and machine learning implementation is in [**netflix_analysis.ipynb**](analysis/netflix_analysis.ipynb)


---

## 📊 Power BI Dashboards

### 🔴 Dashboard 1: Netflix Content Overview

![](dashboards/dashboard_1.png)

---

### 🎯 Dashboard 2: Genre & Rating Insights

![](dashboards/dashboard_2.png)

---

### 🎬 Dashboard 3: Titles, Durations & Origins

![](dashboards/dashboard_3.png)

---

## 📥 Power BI File

You can download and explore the full Power BI dashboard using the file below:

📂 **[netflix_dashboard.pbix](netflix_dashboard.pbix)**

Open this in Power BI Desktop to interact with filters, slicers, and visuals.

---

## 👩‍💻 Author

**Silla Shaju**  
MSc Data Science | Data Analyst Intern at Unified Mentor Pvt Ltd  
https://www.linkedin.com/in/silla-shaju-309b66322?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
