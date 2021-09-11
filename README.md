# Kickstarting with Excel

## Overview of Project

### The purpose of this analysis was to view outcomes of varying theater launches. For theater outcomes by launch date, we wanted to see when theater productions were at their most successful versus their most failed and cancelled throughout the year, This would allow us to see if productions tend to do better in certain months or seasons and plan more releases in the upcoming year during those months primarily to have the highest successful rate posible. For the outcomes by goal amounts, we wanted to see how often a play production was successful based off of their fundraising goal. This wuld allow us to see if play productions with a lower goal are more successful than productions with a higher goal, or vice versa. We could then use this information to set goals for plays moving forward to achieve maximum success.

## Analysis and Challenges

### For the outcomes based on launch date, I first started by creating a pivot table in a new worksheet referencing the kickstarter data worksheet. In this pivot table, my rows consisted of the name of each month of the year while my columns were the outcomes of theater productions (successful, failed, and cancelled). I set my values to be a count of each outcome by month as well. Once this was set, I added a parent catergory and years filter so we can restrict the viewed data as needed. This allowed me to view the amount of successful, failed, and cancelled theater productions month over month. From there, I addeed a line graph to visualize this data as well. While I did not experience difficulty on this portion of the challange, if you were to mix up the data that should be in a column versus a row, this can lead to the data not showing the same numbers in a different manner. However, the line graphwould not be successful at presenting the data due to "successful", "failed", and "cancelled" being invalid x-axis coordinates.

### Analysis of Outcomes Based on Goals

### For the outcomes based on goals challenge, I first started by creatign a table to show the breakdown of successful, failed, and cancelled play productions based on their fundraising goal. Once the table was set up, I used the COUNTIFS function to show the number of plays that fell under each outcome and range of goals. I then used the SUM function to total how many plays fell under each range of goal, regardless of their outcome. Once we had the total, I was able to calculate the percentage of each outcome by dividing the number of successful, failed, or cancelled plays by the total number of plays in that range of goal. Finally, I created a line graph to compare the percentage of successful, failed, and canclled play productions according to their funraising goal to visualize how a play's chance of success can change as it's fundraising goal changes. During this challenge, I made the mistake of selecting the "Pledged Amount" from the kickstarter data instead of the "Goal Amount". This led to me getting data I was not looking for and incorrect results. Thankfully, this was an easy fix once I realized my mistake. To correct this, I went through each COUNTIFS formula and corrected the column of data I was getting the amounts from. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

### The first conclusion I can draw from the data on outcomes versus their launch date is that the number of theater productions are higher in the summer, with a greater success rate. This can directly correlate to winter weather keeping people at home while they tend to be out more during the summer months. Based off of this, we would recommend planning a tehater production during the summer months to give it a greater chance at success. Another conclusion we can draw is roughly on third of theater productions fail or are cancelled. This conclusion can tie into my first conclusion with planning more theater productions into the summer, but it opens up more questions into why such a larger number are failing. To get an answer on this, we would need to analyze the data further so we can make adjustments to lead to a higher success rate. 

- What can you conclude about the Outcomes based on Goals?

### For the outcomes based on goals, I can conclude that when a play production has a fundraising goal of $0-$5000 and $35,000 to $45,000, plays have their highest success rate. All other ranges have either and equal or higher amount of failed productions. The highest chance of a failed prodruction is if a play has a fundraising goal of $45,000 or more. However, most plays had a fundraising goal less than $5,000. What this means in most of the plays were budgetted properly to make their play successful. While we would want to run more analysis on the deomgraphics these plays were targetting towards to see why they were the most successful, this analysis does help us to plan for future plays to follow a similiar fundraising goal for optimal success. 

- What are some limitations of this dataset?

### Some limitations include what demographics each play is targetting, if the plays were advertised, and how each team went about fundraising. While we can see what months and fundraising goals tend to be more successful, and we can plan around this, the additional information would allow us to do a deeper dive into if there are underlying causes on why so many theater productions are failing and why low fundraising goaled plays are thriving. 

- What are some other possible tables and/or graphs that we could create?

### For the outcomes based on data launch, another useful graph we could use would be a clustered column chart. This graph would provide a nice visualization of the amount of failed theater productions versus successful ones compared side by side so that it is easy for the eye to pick up on what months have a substantial difference in successfulo productions. For the outcomes based on goals, a stacked column or bar chart would also work very nicely. This is because each column would reach 100% and show a fantastic comparison of percentages for failed versus successful play productions. 
