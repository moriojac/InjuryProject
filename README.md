<h1>NBA Injury Explorer: Insights for Prevention</h1>
[Project Link](https://moriojac.shinyapps.io/myapp/)

<h2>Description</h2>
This Shiny interactive application visualizes NBA injury data from 2010-2017, allowing users to explore injuries sustained by players and identify potential patterns. Interactive dashboards provide a comprehensive overview of injury trends in professional basketball, ultimately providing insights that can aid in injury prevention.
<br />


<h2>Languages and Utilities Used</h2>

- <b>R</b> 
- <b>ggplot</b>
- <b>Shiny</b>


<h1>Project Process:</h1>

## Data Collection
For this project, data was collected from two primary sources: an NBA injury catalog and an NBA stats catalog, which can be found below.

- [NBA Injuries 2010-2018](https://www.kaggle.com/datasets/ghopkins/nba-injuries-2010-2018)
- [NBA Player Stats](https://www.kaggle.com/datasets/drgilermo/nba-players-stats?select=Seasons_Stats.csv)

(via prosportstransactions.com and basketball-reference.com)

---

## Data Cleaning and Preparation

- **Filtering Data:** Only relevant years (2010-2017) were kept for both stats and injury datasets.
- **Removing Unnecessary Columns:** Duplicate and irrelevant columns were dropped.
- **Standardizing Column Names:** Column names were standardized to ensure consistency across datasets.
- **Merging Datasets:** Data was merged on key attributes—Year, Player, and Team.

---

## Data Visualization & Storytelling
Data is manipulated into several visualizations, categorized into three sections:

- **Injury Visualization:** Providing a comprehensive view of injuries sustained.
- **Change Over Time:** Revealing injury growth, pointing to the need for better injury prevention.
- **Contrast:** Identifying injury risks based on physical attributes and performance metrics.

---

## Interpretation & Decision-Making
The goal of this data is to offer insights that assist professionals in injury prevention, allowing the reader to interpret and make decisions based on the findings.

Insights from the data can help teams develop targeted injury prevention strategies, such as **load management** for high-minute players and **conditioning/workout programs** based on position-specific vulnerabilities.
