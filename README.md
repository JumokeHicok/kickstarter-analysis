# An Analysis of Kickstarter Campaigns

## Overview of Project

The purpose of this analysis is to look for relationships between theater campaign success rates and launch dates as well as success rates based on funding goals for plays.  This analysis will be used to...

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To analyze outcomes based on launch date I first added a column at the end of the data to pull only the year the campaign was launched.  I then created a pivot table off of the entire dataset and filtered it down to just theater campaigns.  Since we are analyzing the data based on launch date, I used the Date Created field for my rows to show launch date by month.  Here is a chart of the data:

![Theater_Outcomes_vs_Luanch](https://user-images.githubusercontent.com/108200597/177053044-27a8fa2e-afca-4572-9195-b8b6123f49be.png)


### Analysis of Outcomes Based on Goals
To analyze outcomes based on goal amount I used Countifs formulas to calculate number and percentage of successful, failed, and canceled projects.  I used that table to create a line chart depicting the outcome percentages by incremental goal amount.  This is what it shows:

![Outcomes Based on Goal](https://user-images.githubusercontent.com/108200597/177053103-3f364a9f-15ac-4911-8da0-3425c14da4ab.png)


### Challenges and Difficulties Encountered

## Results

-  One conclusion we can make about the outcomes based on **launch date** is that May, June, and July have the most campaigns launched and also have the highest success rates.  You can see that the successful outcomes are not driven by number of launches alone by looking at the gap between the successful and failed lines on the chart.  The two lines are furthest apart in May, June, and July meaning the success rate is highest for those three months of the year.  
- Another conclusion we can make about the outcomes based on **launch date** is that December would not be an ideal month to launch a theater campaign.  Not only is the number of launches the lowest for the entire year, but the rate of success is lowest.  Looking at the chart you can see that the points for successful and failed compaigns touch in the month of December meaning that approximately the same number of campaigns succeed and fail when launched in that month.

- One conclusion that we can make about the outcomes based on **goal amount** is that the higher the goal is, the more likely it is to fail.  Campaigns with goals less than $5,000 are the most likely to succeed.  

- One limitation of this dataset is that it does not contain a full year of data for 2017.  Outcomes for January and February will be elevated because that is all that's available so far for 2017.  Another limitation is that we do not have as much data at the higher goal levels.  The reason for the higher fail rate at those levels could be unrelated to the goal amount.

- What are some other possible tables and/or graphs that we could create?
