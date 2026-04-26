# 🏏 IPL Power BI Dashboard

## 🚀 Project Overview

This project is an interactive IPL (Indian Premier League) dashboard built using Power BI.
The goal was to replicate a real-world cricket analytics platform similar to Cricbuzz and the official IPL website, while applying data analytics and visualization skills.

---

## 🎯 Motivation

I am a passionate cricket fan and always wanted to connect my interest in cricket with my field of study in Computer Science, especially Data Analytics.

With a strong mathematics background and growing skills in Power BI, this project became the perfect opportunity to combine:

* 📊 Data Analytics
* 🏏 Cricket Passion

The timing also aligned perfectly with the IPL season and the completion of my Power BI learning, making it the right moment to build a complete IPL dashboard from scratch.

---

## ⚙️ Features

* 📊 Interactive IPL dashboard (similar to Cricbuzz/IPL site)
* 🏆 Player statistics (Orange Cap, Most Wickets, etc.)
* 📅 Match fixtures and results
* 📈 Points table with rankings
* 👥 Squad analysis page
* 🎨 Custom UI using HTML + CSS inside Power BI
* 🔄 Dynamic filtering using slicers
* 🔒 Multiple hidden navigation pages

---
> Note: The dashboard contains multiple hidden pages and dynamic navigation handled within Power BI.
---

## 📂 Data Source

Getting the data was one of the most challenging parts of this project.

* 🔴 **Live match data** → fetched using APIs
* 📊 **Static data (Most Runs, Wickets, Dots, etc.)** → manually collected from the official IPL website and stored in Excel

---

## 📂 Data Sourcing & Engineering
Procuring and shaping the data was the most rigorous phase of this project, taking up roughly a third of the total development time.

* **Data Collection:**
  * **Live Match Data:** Fetched dynamically using APIs.
  * **Historical/Milestone Data:** Extracted and compiled manually from the official IPL website into Excel structures.
* **ETL & Data Transformation:**
  * Cleaned and normalized raw datasets, systematically handling nulls and irrelevant artifacts.
  * Renamed and remapped cryptic API column headers (e.g., converting `ng-binding1` to readable metrics) for seamless DAX integration.
  * Resolved entity inconsistencies across distinct datasets (e.g., standardizing "Bangalore" vs. "Bengaluru" to ensure perfect relational mapping).
  * Modeled multiple disjointed tables to mirror the official IPL database structure.
---
## ⚠️ Challenges Overcome
* **Data Scarcity & Quality:** Sourcing reliable, complete, and free API data for the IPL required extensive searching and manual patching.
* **Complex Data Modeling:** Handling inconsistent naming conventions and creating relationships without clean primary keys.
* **Visual Limitations:** Overcoming native Power BI image rendering and CORS issues by utilizing image proxies and writing pure HTML/CSS inside Power BI.
* **Version Control:** Lost significant progress early on due to an unsaved file crash—a hard-learned lesson in continuous saving!

---

## 🧠 Learnings

* Advanced DAX functions and logic building
* Using HTML & CSS inside Power BI visuals
* Data cleaning and transformation techniques
* Importance of consistent data modeling
* Handling real-world messy datasets
* Importance of saving work frequently
* Most importantly: **Patience during long debugging and cleaning phases**

---

## ⏱️ Project Timeline

* Total Time: **~25 Days**
* Data Cleaning & Transformation: **7–8 Days (most challenging part)**

---

## 🚀 Future Improvements

* Real-time live match integration
* More advanced analytics (player comparisons, predictions)
* Improved UI/UX and animations
* Mobile-friendly dashboard layout

---
> Note: The dashboard contains multiple hidden pages and dynamic navigation handled within Power BI.
---

## 📸 Project Preview
* `images/Home.jpg`
* `images/Overview.jpg`
* `images/points_table.png`
* `images/Squards.jpg`
* `images/Most_Runs.png`
---

## 📁 Project Structure

```
IPL-PowerBI-Dashboard/
│
├── 📊 IPL_Dashboard.pbix        # Main Power BI dashboard file
│
├── 📁 Data/                     # Raw and processed datasets
│   ├── records.xlsx
│   ├── schedule.xlsx
│   └── mostruns.xlsx
│
├── 📁 Images/                   # Screenshots used in README
│   ├── home.png
│   ├── overview.png
│   ├── points_table.png
│   ├── squad.png
│   └── top_player.png
│
└── README.md                   # Project documentation
```
> Note: The dashboard contains multiple hidden pages and dynamic navigation handled within Power BI.
---

## 💡 Final Thought

This project represents the intersection of my passion for cricket and my skills in data analytics.
It was not just about building a dashboard, but about solving real-world data problems and creating something meaningful.
