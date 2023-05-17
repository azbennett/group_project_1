
**#Project Title:**  
 - NYC Analysis of Accident Data - crash_data.ipynb

**#Team Members:**  
 - Ginger Francione
 - Joan Montilla
 - Steve Bennett

**#Project Description/Outline:**  
 - Comparitive Analysis of accident data based over time, borough locations, or seasons.
 - Potential business to use this with is through Traffic Systems Inc - Areas of high risk may need further study
 - Department Of Transportation could also utitlize this data for safety awareness or trouble shooting dangerous intersections.

**#Questions to Answer:**   
Steve
 - Can the data visualize areas of concern?  Does each borough or all of NYC have specific areas that are more likely to have accidents?
 - During normal commute times - is there a differnce in number of crashes before or after a workday is completed?

Joan
 - Are specific NYC Boroughs more likely to have accidents than others? (Including checking for population normalization)
 - Compare if fatality accidents had multiple vehicles more often than single car accidents. 
 - Determine if accidents are more likely during certain months.

Ginger
 - Can we better visualize the number of crashes based on the time of day, month, or number of vehicles through scatter plots.
 - Does winter or summer have any effect on the number of accidents?


**#Datasets to be used:**  

 - [https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes  ](https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes)
 - Motor Vehicle Collisions - Crashes - 
 - The Motor Vehicle Collisions crash table contains details on the crash event. Each row represents a crash event. The Motor Vehicle Collisions data tables contain information from all police reported motor vehicle collisions in NYC. The police report (MV104-AN) is required to be filled out for collisions where someone is injured or killed, or where there is at least $1000 worth of damage  

 - US Census 2021 Data 
    - https://www.census.gov/data/developers/data-sets.html#:~:text=The%20Census%20Bureau's%20Application%20Programming,users%20to%20create%20custom%20queries.
    - https://www.census.gov/data/developers/data-sets/popest-popproj/popest.html
    - https://api.census.gov/data/2021/pep/population/variables.html

 - https://portal.311.nyc.gov/article/?kanumber=KA-02877  
    - List of all counties and their respective Borough name need to convert official county name into the commonly known names

**#Additional files generated / used:**  
 - Main data set from data.gov
    - git\group_project_1\data\nyc_mv_crash_data_truncated4.csv

 - Generated data:
    - git\group_project_1\heatmaps\*.html
        - Multiple generated heatmaps for all of NYC and each borough
    - all_crashes.html - Point HVPLOT of all crashes in NYC
    - fatal_crashes.html - Point HVPLOT of all fatal crashes in NYC