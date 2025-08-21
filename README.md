# 🦠 COVID-19 Global Data Tracker

## 📌 Project Description
This project tracks global COVID-19 data and visualizes trends in cases, deaths, and vaccinations using Python.  
It is designed for learners to practice data analysis, exploratory data analysis (EDA), and visualization with real-world datasets.

By the end, you’ll have a data-driven report with charts and insights, suitable for presentation or publishing.

---

## 🚩 Project Objectives
- ✅ Import and clean COVID-19 global data  
- ✅ Analyze time trends (cases, deaths, vaccinations)  
- ✅ Compare metrics across countries/regions  
- ✅ Visualize trends with charts and maps  
- ✅ Communicate findings in a Jupyter Notebook or PDF report  

---

## 🗂️ Project Segments

### 1️⃣ Data Collection
- Source: [Our World in Data COVID-19 Dataset](https://ourworldindata.org/coronavirus)  
- File: `owid-covid-data.csv`  
- Alternative source: Johns Hopkins University GitHub Repository  

---

### 2️⃣ Data Loading & Exploration
- Load dataset using **pandas**  
- Explore structure (`df.head()`, `df.columns`)  
- Check for missing values  

---

### 3️⃣ Data Cleaning
- Filter countries of interest (e.g., Kenya, USA, India)  
- Convert dates to datetime  
- Handle missing values with `fillna()` or interpolation  

---

### 4️⃣ Exploratory Data Analysis (EDA)
- Cases and deaths over time  
- New daily cases and comparison by country  
- Death rate = `total_deaths / total_cases`  

📊 **Visuals:** Line charts, bar charts, optional heatmaps  

---

### 5️⃣ Vaccination Analysis
- Vaccination rollouts over time  
- Compare % of population vaccinated  

📊 **Visuals:** Line charts, pie charts  

---

### 6️⃣ Optional: World Map Visualization
- Use **Plotly Express** or **geopandas**  
- Choropleth map of global case density or vaccination rates  

---

### 7️⃣ Insights & Reporting
- Summarize 3–5 key insights  
- Highlight anomalies or patterns  
- Document findings with code, charts, and markdown  

---

## 🛠️ Tools Used
- Python (Jupyter Notebook)  
- pandas  
- matplotlib  
- seaborn  
- plotly (optional for interactive maps)  

---

## 📂 Repository Structure
