# 🚧 SCT\_DS\_04

**Internship Task 04 – US Traffic Accident Data Analysis using Python & Visualization**
💼 *SkillCraft Technology* | 📅 *August 2025*

---

### 📌 Overview

Analyze and visualize a large-scale U.S. traffic accident dataset to uncover key patterns and contributing factors.

* Dataset: Synthetic dataset modeled after the **US Accidents (7.7M rows)** dataset.
* Focus: Understand how weather, time, location, and road conditions impact accident severity.
* Tools used: `pandas`, `matplotlib`, `seaborn`, `folium`, `scikit-learn`.

---

### 📁 Dataset Details

**Source:** Synthetic data (based on real US Accident data schema)

**Key Columns Used:**

* `Severity`: Accident severity (1–4, where 4 is most severe)
* `Start_Time`: Date and time when the accident began
* `Weather_Condition`, `Visibility`, `Temperature`, `Humidity`: Weather factors
* `Start_Lat`, `Start_Lng`: Location of the accident
* `Bump`, `Crossing`, `Amenity`, `Give_Way`: Road condition flags
* `Sunrise_Sunset`: Time of day (Day/Night)

---

### 📊 Analysis & Visualization Features

✅ **Datetime Feature Engineering** – Extracted `hour` and `day of week` from timestamps


✅ **Exploratory Analysis** – Countplots and boxplots reveal patterns


✅ **Geospatial Clustering** – Accident hotspots identified using DBSCAN and plotted on interactive `folium` map


✅ **Correlation Mapping** – Severity compared with weather and visibility


✅ **Road Conditions Impact** – Bar plots for impact of road features like bumps, crossings, etc.


✅ **Time Series Patterns** – Accidents peak during commute hours and weekdays

---

### ✅ Insights Summary

🌞 **Accidents are more frequent during daytime**, especially during peak hours.


🌦 **Weather conditions** like fog or rain reduce visibility and increase severity.


📍 **Hotspots** detected in specific lat-long clusters using DBSCAN.


🏞 **Road features** like crossings, bumps, and give-way signs correlate with accident occurrence.


🗓 **Weekdays see higher accident frequency** compared to weekends.


👁️‍🗨️ **Low visibility** is directly associated with higher severity levels.

---

### 🧠 Learnings

🛠 Performed end-to-end EDA and clustering on real-world-like accident data


📍 Learned to apply **geospatial clustering** using DBSCAN and Haversine distance


📈 Practiced advanced data visualization with `seaborn` and `folium`


🧮 Understood how **weather and road factors contribute to accident severity**


📊 Developed skills in extracting actionable insights from big datasets

---

### ▶ How to Run

1. Clone the repository or create a new Python project in **VS Code**
2. Place `Task04_Synthetic_Accident_Data.csv` inside your project folder
3. Run the notebook: `Task04_Accident_Analysis_Notebook.ipynb`
4. View plots for time, weather, road conditions, and geospatial clustering
5. Open `Task04_Hotspots_Map.html` to explore accident hotspots interactively
6. (Optional) Extend the analysis using ML models like Random Forest or Gradient Boosting

