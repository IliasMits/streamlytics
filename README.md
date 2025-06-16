# 📊 Data Behind the Binge

_Uncovering what makes streaming content successful, one dataset at a time._

---

## 🎬 Project Overview

In an era where streaming platforms dominate entertainment, what separates a hit show from a forgotten flop?  
**Data Behind the Binge** dives into data from Netflix, IMDb, and more to reveal patterns and insights into what makes streaming content successful.

---

## ❓ Key Questions Explored

- **Which genres dominate streaming platforms?**
- **Do runtime, release year, or cast affect ratings?**
- **How do Netflix titles compare to IMDb’s top-rated shows?**
- **Can we predict a show’s popularity based on its metadata?**

---

## 📦 Data Sources

- **Netflix Shows Dataset** – [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **TMDb API** – [TMDb](https://www.themoviedb.org/documentation/api)

---

## 🛠️ Tools & Libraries

- **Languages & Frameworks:** Python
- **Data Analysis:** pandas, NumPy
- **Visualization:** Matplotlib, Plotly
- **APIs:** Requests, TMDb API
- **Dashboard (Optional):** Tableau

---

## 🧠 Key Skills Demonstrated

- Data wrangling & cleaning
- Exploratory Data Analysis (EDA) & statistical analysis
- API integration
- Data visualization & storytelling
- GitHub project structure & documentation

---
## 🔧 Project Steps

### 1. **Obtaining Data**
- Downloaded raw Netflix dataset from Kaggle
- Collected metadata from TMDb API for enrichment

### 2. **Cleaning Data**
- Standardized column names and formats
- Converted date fields to datetime
- Enriched the data to include the popularity and vote scores
- Removed duplicate entries

### 4. **Saving Clean Data**
- Raw: `data/raw/netflix_titles.csv`, 'data/raw/metadata.csv'
- Clean: `data/clean/netflix_titles_cleaned.csv`
## 🚀 Get Started

Clone the repository and install requirements:

```bash
git clone https://github.com/IliasMits/streamlytics.git
cd streamlytics
pip install -r requirements.txt
