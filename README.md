# Kickstarter Analysis 
---
## Overview of Project 
The purpose of this analyis is to find trends to show Louise on different campaigns in relation to their respective launch dates and funding goals. We will be strictly looking at these with subcategories in plays and theater which are topics which line with Louise's interest. The main goal for this analysis is to find trends in successful plays to set aim at a target goal for Louise to begin her funding goal and an accurate time at which Louise should have a launch date within the year. 
---
## Analysis and Challenges
Analyzing the data and looking at trends we were able to filter out some of the data that didn't matter to Louise. For our two charts Outcomes Based on Launch Date and Outcomes Based on Goals, we were able to narrow the data to theater for one and plays for the other making it more suitable to Louise to find the data that she wants. For the data corresponding to the outcomes based on launch dates we were able to format a pivot table. In this pivot table we were able to find the best month to launch a theater campaign. The challenge during this was being able to sort the data by each month but after careful investigation we were able to come to a finished pivot table.
![Pivot Table For Theater Analysis](https://github.com/mckjack/kickstarter-analysis/blob/main/Pivot%20Table%20for%20Theater%20Analysis.png)
- From that pivot table we were able to make a line graph and show the following 
---
![Theater_Outcomes_vs_Launch](https://github.com/mckjack/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
---
For our second analysis we looked at outcomes of play campaigns to see what an ideal goal to start with would be to ensure that the campaign is successful. In excel we able to use the COUNTIFS() function to find the data for successful, failed, and cancelled play campaigns. This was a challenging part due to the fact that the boundaries on the goal had to be ensured to get the accurate data. An example of the code would look like,
> =COUNTIFS(Kickstarter!$D:$D, ">=5000",Kickstarter!$D:$D, "<=9999",Kickstarter!$F:$F,"successful",Kickstarter!$R:$R,"plays")
Using this we found the data we needed and formatted it into a table looking like, 
![Table of Outcomes Based on Goals](


