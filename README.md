# Kickstarter Analysis 
---
# Overview of Project 
The purpose of this analyis is to find trends to show Louise on different campaigns in relation to their respective launch dates and funding goals. We will be strictly looking at these with subcategories in plays and theater which are topics which line with Louise's interest. The main goal for this analysis is to find trends in successful plays to set aim at a target goal for Louise to begin her funding goal and an accurate time at which Louise should have a launch date within the year. 
---
## Analysis and Challenges
Analyzing the data and looking at trends we were able to filter out some of the data that didn't matter to Louise. For our two charts Outcomes Based on Launch Date and Outcomes Based on Goals, we were able to narrow the data to theater for one and plays for the other making it more suitable to Louise to find the data that she wants. For the data corresponding to the outcomes based on launch dates we were able to format a pivot table. In this pivot table we were able to find the best month to launch a theater campaign. The challenge during this was being able to sort the data by each month but after careful investigation we were able to come to a finished pivot table.
![Pivot Table For Theater Analysis](https://github.com/mckjack/kickstarter-analysis/blob/main/Pivot%20Table%20for%20Theater%20Analysis.png)
- From that pivot table we were able to make a line graph and show the following 
![Theater_Outcomes_vs_Launch](https://github.com/mckjack/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
---
For our second analysis we looked at outcomes of play campaigns to see what an ideal goal to start with would be to ensure that the campaign is successful. In excel we able to use the COUNTIFS() function to find the data for successful, failed, and cancelled play campaigns. This was a challenging part due to the fact that the boundaries on the goal had to be ensured to get the accurate data. An example of the code would look like,
> =COUNTIFS(Kickstarter!$D:$D, ">=5000",Kickstarter!$D:$D, "<=9999",Kickstarter!$F:$F,"successful",Kickstarter!$R:$R,"plays")
---
Using this we found the data we needed and formatted it into a table looking like, 
![Table of Outcomes Based on Goals](https://github.com/mckjack/kickstarter-analysis/blob/main/Table%20of%20Outcomes%20Based%20on%20Goals.png)
- From this table we were able to produce another graph that resembled the following,
![Outcomes_vs_Goals](https://github.com/mckjack/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)
---
## Results
The conclusions we can take away from this data is that for theater outcomes based on launch date, it appears that the best months to launch a theater campaign is May or June simply because those were the two months that had the highest count of successful theater campaigns. However, another takeaway is we also see that in these two months the total of launched campaigns are the highest making the failed campaigns a high count as well. Therefore we must look at the initial goal of the campaign to ensure that we can find a target to have a successful campaign launch. We see that the data for initial goal shows that having a goal of less than $4999 will ensure a 73% chance of being successful and even a goal of less that $1000 will ensure a 76% of being successful. Therefore we recommend a intial goal in that range to give the best chance of the campaign being successful. Lastly, the only limitation that this data perceives is it doesn't show the specific play that will have the most success. Some plays may not have as much success as the others.


