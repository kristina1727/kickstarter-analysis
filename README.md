# Kickstarting with Excel - Campaign Successfulness

## Overview of Project

### Purpose
To conduct an analysis of Kickstarter campaign data to determine how different campaign fared when comparing the campaigns outcome against the launch date and funding goal.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The first analysis I completed, Theater Outcomes Based on Launch Date, looks at theater campaigns by the month the campaign started and the campaigns outcome focusing on those that were successful, failed and canceled. To do this I constructed a pivot table placing the date the campaign started in the rows container and outcomes in both the columns and values containers. To ensure the data provided relevance to the client, I then added the category to the filter container and filtered the data to only look at the theater category. I also added the year field to the filter container which will allow, should the client be interested, to look at the success of theater campaigns in different years. I created a line chart shown below from the pivot table to visualize my findings. 

![](Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The second chart, Outcomes vs Goal, analyzes the data by looking at a campaigns fundraising goal and the outcome, again focusing on those campaigns that were successful, failed and canceled. I further narrowed this down to look only at those theater campaigns that fell into the play subcategory. To complete this analysis, I first determined goal ranges, then using COUNTIFS formulas I was able to calculate the number of campaigns that fell in each range by their outcome. I then totaled the total number of campaigns within each fundraising goal range using the sum formula. This calculation allowed me to determine what percent of campaigns in each range were successful, failed or cancelled. The line chart below demonstrates the findings from the analysis.

![](Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

One of the challenges I encountered was with my COUNTIFS formula when conducting my analysis of outcomes based on goals. I did need to google how to construct the formula. Then verifying my data I discovered that my counts were not lining up. I discovered that I excluded using the "=" symbol in my formula when referring to the ranges, thus excluding campaigns from my count. While not a challenge face in this exercise, a potential difficulty that could have been encountered was not understanding what some of the fields referenced (staff pick, spotlight).

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    1. Campaigns staring in the spring have a 65% chance of being successful. With those campaigns starting in May have the highest success rate at 67%. 
    2. December is the least successful month to launch a campaign with only 47% of campaigns being successful. One could assume the lack of campaign success is due to the holiday season.

- What can you conclude about the Outcomes based on Goals?

    1. Campaigns with the highest success rate, 76%, were those that had a fundraising goal of less than $1,000. Though those that had a goal of less than $5,000 also had a high success rate of 73%.
    2. As a general rule, the higher the goal the lower the success rate. However, this does not hold true for those campaigns with a fundraising goal between $35,000-$44,999. Their success rate was 67%, but there were much fewer campaigns beteen that range. 

- What are some limitations of this dataset?

    A few limitations of the data set is that we are only looking at fundraising campaigns that were initiated through Kickstart and not other fundraising platforms. Other platforms may be more or even less successful. Another limitation is that we don't know how they advertised their kickstart campaign, was it only word of mouth, did they fliers, post on social media platforms, etc. 

- What are some other possible tables and/or graphs that we could create?

    Below are a few ideas of additional visuals we could have created:
    - Campaign Success by Year
    - Campaign Success by Country
    - Campaign Success by Length of Campaign


