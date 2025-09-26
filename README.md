# netflix-eda
# 📊 Netflix Dataset – Exploratory Data Analysis (EDA)

## 📝 Project Overview
This project presents an **Exploratory Data Analysis (EDA)** of a Netflix dataset containing **8,790 entries**.  
The analysis explores:
- Content distribution by type and country
- Release years
- Ratings
- Movie durations
- Genre distribution
- Correlations between variables

---

## 📂 Dataset Overview
- **Total Entries:** 8,790  
- **Columns:** 10  
- **Data Types:** Mostly categorical (object) + one numerical (`release_year`)  
- **Missing Values:** None  
- **Duplicates:** None  

### Columns:
1. `show_id` – Unique identifier  
2. `type` – Movie or TV Show  
3. `title` – Show title  
4. `director` – Director name  
5. `country` – Country of origin  
6. `date_added` – Date added to Netflix  
7. `release_year` – Release year  
8. `rating` – Age/content rating  
9. `duration` – Duration (minutes or TV seasons)  
10. `listed_in` – Genres/categories  

---

## 🔎 Key Findings

### 1️⃣ Content Type Distribution
- **Movies:** 6,126 (~70%)  
- **TV Shows:** 2,664 (~30%)  

### 2️⃣ Top Contributing Countries (Top 10)
United States, India, United Kingdom, Pakistan, Canada, Japan, South Korea, France, Spain, Turkey.

### 3️⃣ Release Year Distribution
- Peak content production **after 2015**.  
- Majority of titles from **2017–2021**.  

### 4️⃣ Ratings Distribution
- Most popular ratings: **TV-MA, TV-14, TV-PG, TV-Y7**.  
- Reflects a mix of adult and family-friendly content.  

### 5️⃣ Duration Analysis (Movies Only)
- Most movies: **80–120 minutes**.  
- Few exceed 150 minutes.  

### 6️⃣ Genre Distribution (Top 10)
Documentaries, Stand-Up Comedy, Dramas, International Movies, Comedies, Action & Adventure, Children & Family Movies, Romantic TV Shows, Crime TV Shows, TV Dramas.

### 7️⃣ Correlation Analysis
- Label Encoding applied to categorical variables.  
- Weak-to-moderate correlations across features.  
- Stronger relationship between `type` & `rating` and `release_year` & `rating`.

---

## 📊 Visualizations Summary
- **Countplots:** Movies vs TV Shows  
- **Bar Charts:** Top 10 countries & genres  
- **Histograms:** Release years & movie durations  
- **Boxplots:** Duration vs Ratings  
- **Heatmap:** Feature correlations  

---

## 📝 Conclusion
- Netflix library is **movie-dominated**, strongly represented by the **US and India**.  
- Content production has grown significantly in recent years.  
- Wide range of **ratings and genres** caters to both adults and families.  
- **Duration patterns** suggest Netflix prefers standard-length films (80–120 minutes).  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn (Label Encoding)

---

## 🚀 How to Run
1. Clone this repository.  
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
