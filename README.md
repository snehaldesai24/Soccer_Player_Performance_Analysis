# ⚽ Soccer Players Performance Analysis

## 🧠 Project Overview
The **Soccer Players Performance Analysis** project focuses on analyzing player statistics such as ratings, wages, values, and nationalities to uncover insights about player performance, market value, and club-level trends.  
This project uses **Python, SQL, and Power BI** for end-to-end data analysis — from data cleaning and transformation to interactive dashboard visualization.

---

## 🎯 Objective
To perform detailed analysis of soccer player data and visualize insights through KPIs and charts that highlight player performance, wage structure, market values, and club efficiency.

---

## 🛠️ Technologies Used
This project combines multiple tools and technologies for efficient data handling and visualization:

- **Python (Pandas, NumPy, Matplotlib):** Used for data cleaning, handling missing values, and preprocessing the dataset for analysis.  
- **SQL (SSMS Tool):** Used for data extraction, aggregation, and transformation to structure the dataset and derive analytical metrics.  
- **Power BI:** Used for building interactive dashboards and visualizing player performance metrics, club comparisons, and nationality insights.

---

## 📊 KPIs Overview
The dashboard provides the following key performance indicators:

1. **Average Rating**
2. **Average Age**
3. **Average Value (€)**
4. **Average Wage (€)**

These KPIs offer a quick summary of overall player performance and financial distribution across clubs and nationalities.

---

## 📈 Analysis & Visualizations

### 🔹 1. Overview Section
- **Chart:** Wage Distribution (Clustered Bar Chart)  
  *Displays the top players and their respective wages. Sorted by wage in descending order with gradient colors for clarity.*

- **Chart:** Top 10 Players by Market Value (Treemap)  
  *Highlights the most valuable players in the dataset, showcasing the market leaders.*

- **Chart:** Highest Rated Players by Overall and Potential (Clustered Column Chart)  
  *Compares each player’s overall rating with their potential rating to identify growth potential.*

---

### 🌍 2. Nationality Analysis
- **Map Visual:** Displays nationalities with bubble sizes representing total player value (€).  
- **Bar Chart (Average Rating per Country):** Shows the average overall rating of players by nationality.  
- **Bar Chart (Players per Country):** Highlights the count of players from each country.

---

### 🏟️ 3. Club Analysis
- **Bar Chart – Clubs with Highest Market Value:**  
  Displays top clubs ranked by total market value.  
  *Insight:* Real Madrid leads with approximately €841M, followed by Liverpool (€761M) and Manchester City (€722M).  

- **Treemap – Average Player Rating by Club:**  
  Visualizes clubs based on the average player rating using color intensity.  
  *Insight:* Real Madrid, FC Barcelona, and Inter have the highest-rated squads (~78–79).  

- **Line Chart – Wage Bills by Club:**  
  Illustrates wage expenditures per club.  
  *Insight:* Top spenders include Real Madrid, Liverpool, and Manchester City, exceeding €3M in total wages.

---

## 💡 Insights
- Top clubs maintain high wages and player market values but also demonstrate strong average ratings.  
- Some mid-tier clubs achieve competitive performance with lower financial investment, showing cost efficiency.  
- Player distribution and average ratings vary significantly across nationalities, with certain countries dominating top performance tiers.

---

## 📁 Project Structure

Soccer-Players-Performance/
│
├── Data/ # Dataset files (CSV/Excel)
├── SQL/ # SQL queries used for analysis
├── Python/ # Python scripts for data cleaning & preprocessing
├── PowerBI/ # Power BI dashboard files (.pbix)
└── README.md # Project documentation

---
## 🚀 How to Run the Project

1. **Data Preparation (Python)**
   - Load dataset using Pandas.
   - Handle missing values and clean data.
   - Export processed data to CSV for SQL/Power BI.

2. **Data Transformation (SQL)**
   - Use SQL queries to aggregate and filter relevant metrics.
   - Export the output tables for visualization.

3. **Visualization (Power BI)**
   - Import data into Power BI.
   - Create KPIs and visuals as described above.
   - Apply gradient colors, legends, and tooltips for better readability.

---

## 🏁 Conclusion
The Soccer Players Performance Analysis dashboard effectively connects data-driven insights with visual storytelling, helping stakeholders understand performance distribution, financial disparities, and growth potential across players, clubs, and countries.
