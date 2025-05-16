<h1>NBA Injury Explorer: Insights for Prevention - <a href="https://moriojac.shinyapps.io/myapp/">Project Link</a> </h1>


<h2>Description</h2>
This Shiny interactive application visualizes NBA injury data from 2010-2017, allowing users to explore injuries sustained by players and identify potential patterns. Interactive dashboards provide a comprehensive overview of injury trends in professional basketball, ultimately providing insights that can aid in injury prevention.
<br />


<h2>Languages and Utilities Used</h2>

- <b>R</b> 
- <b>ggplot</b>
- <b>Shiny</b>
- <b>shinyapps.io</b>

<br><br>

<div align="center">
  <h1>Project Process</h1>
</div>

<table width="100%" style="table-layout: fixed;">
  <tr>
    <td align="center" valign="top" width="25%">
      <div>
        <img src="InjuryProject_P1.png" style="width: 90%; height: 300px; object-fit: cover;" />
        <b>Data Collection</b>
        <br>
        <h6 style="text-align: center; min-height: 150px; font-size: 2px;">
          For this project, data was collected from two primary sources: an NBA injury catalog and an NBA stats catalog, which can be found below.
          <br><br> <a href="https://www.kaggle.com/datasets/ghopkins/nba-injuries-2010-2018">NBA Injuries 2010-2020</a>
          <br><br> <a href="https://www.kaggle.com/datasets/drgilermo/nba-players-stats?select=Seasons_Stats.csv">NBA Player Stats</a>
          <br><br> (via <a href="https://prosportstransactions.com/"> prosportstransactions.com </a> and <a href="https://www.basketball-reference.com/"> basketball-reference.com</a>)
        </h6>
      </div>
    </td>
    <td align="center" valign="top" width="25%">
      <div>
        <img src="InjuryProject_P2.png" style="width: 90%; height: 300px; object-fit: cover;" />
        <b>Data Cleaning and Preparation</b>
        <h6 style="text-align: center; min-height: 150px;">
          - Filtering Data: Only relevant years (2010-2017) were kept for both stats and injury datasets.
         <br><br> - Removing Unnecessary Columns: Duplicate and irrelevant columns were dropped.
         <br><br> - Standardizing Column Names: Column names were standardized to ensure consistency across datasets.
         <br><br> - Merging Datasets: Data was merged on key attributes—Year, Player, and Team.
        </h6>
      </div>
    </td>
    <td align="center" valign="top" width="25%">
      <div>
        <img src="InjuryProject_P3.png" style="width: 90%; height: 300px; object-fit: cover;" />
        <b>Data Visualization & Storytelling</b>
        <h6 style="text-align: center; min-height: 150px;">
          Data is manipulated into several visualizations, categorized into three sections:
         <br><br> - Injury Visualization: Providing a comprehensive view of injuries sustained.
         <br><br> - Change Over Time: Revealing injury growth, pointing to the need for better injury prevention.
         <br><br> - Contrast: Identifying injury risks based on physical attributes and performance metrics.
        </h6>
      </div>
    </td>
    <td align="center" valign="top" width="25%">
      <div>
        <img src="InjuryProject_P4.png" style="width: 90%; height: 300px; object-fit: cover;" />
        <b>Interpretation & Decision-Making</b>
        <h6 style="text-align: center; min-height: 150px;">
          The goal of this data is to offer insights that assist professionals in injury prevention, allowing the reader to interpret and make decisions based on the findings.
         <br><br> Insights from the data can help teams develop targeted injury prevention strategies, such as load management for high-minute players and conditioning/workout programs based on position-             specific vulnerabilities.
        </h6>
      </div>
    </td>
  </tr>
</table>



