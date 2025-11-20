# Netflix Content Analytics Dashboard (Power BI)

## 📌 Project Overview
This project explores the global Netflix catalog using Power BI.  
The goal is to analyze content distribution, release trends, content types, ratings, and duration insights.  
Using DAX measures and interactive visuals, I built a dynamic dashboard that helps users understand how Netflix content varies across countries and years.

---

## 🎯 Key Features & KPIs

### ✔ DAX Measures Created
- **Total Movies**
- **Total TV Shows**
- **Total Titles (Movies + TV Shows)**

### ✔ Interactive Visuals
1. **Map Chart – Number of TV Shows by Country**  
   Shows geographic distribution of Netflix TV show availability.

2. **Bar Chart – Movies vs TV Shows by Release Year**  
   Identifies release trends and growth of content over time.

3. **Pie Chart – Rating Distribution**  
   Shows content classification (TV-MA, TV-14, PG, etc.)

4. **Donut Chart – Duration Buckets**  
   Example buckets:  
   - 0–30 min  
   - 30–60 min  
   - 60–120 min  
   - 120+ min  

---

## 📁 Dataset Used
Dataset includes:
- Title  
- Country  
- Release Year  
- Type (Movie/TV Show)  
- Rating  
- Duration  
- Description  
- Category / Genre  

(Netflix dataset typically from Kaggle)

---

## 🧩 Data Modeling & Transformations
- Cleaned null values in country, rating, and duration.
- Split duration into numeric + unit.
- Created **Duration Bucket** column in Power Query.
- Built **measures** for Movies, TV Shows, Total Titles.
- Used a **calendar table** for time-based analysis (release_year).

---

## 📊 Dashboard Highlights

### 🔹 Content Type Insights
- Count of Movies vs TV Shows
- Distribution over years

### 🔹 Geographic Insights
- TV Shows available by country (filled map)

### 🔹 Rating Analysis
- Which ratings dominate Netflix content?

### 🔹 Duration Analysis
- Movie/episode length grouped into buckets

---

## 🧠 Business Questions Answered
- How many movies and TV shows does Netflix have?
- Which countries contribute the most TV Shows?
- What types of content have increased over the years?
- What content rating is most common?
- How is content distributed across duration buckets?

---

## 🛠 Tools Used
- **Power BI**
- **DAX**
- **Power Query**
- **Data Modeling**

---

## 📌 Outcome
The dashboard provides a clear and interactive view of Netflix content trends, helping users explore global availability, year-wise growth, ratings, and duration patterns. It acts as a strong example of end-to-end BI reporting and DAX-based KPI creation.

---

## 👤 Author
Komal Bharambe — Data Analyst
