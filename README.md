# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends
## Project Overview
Louise's play "Fever" came close to its funding goal in a short period of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset I have visualized campaign outcomes based on their launch dates and their funding goals.
### Purpose
The purpose of this analysis is to help uncover trends with in the data that will help Louise gain insight into how different factors (launch date and funding goals) affect the outcomes of plays.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
In this portion of the report I will take a look at how the launch date affects the outcome of a theater campaign. To do this I created a pivot table in excel to see how many plays were successful, failed, or canceled based on the month of the year in which they were launched. By entering the correct fields into the apropriate areas, grouping, sorting, and filtering I was able to structure the data and count the outcomes of these plays based on the month in which they were launched.
![Pivot_Table_Outcomes_Based_on_Launch_Date](https://user-images.githubusercontent.com/111163264/187095192-d18021fc-ea9c-4d3a-ae89-c2ff6e2dc138.PNG)
Next, I created line chart to visualize the data being presented in the pivot table.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111163264/187094806-8d1c3843-7309-416a-b652-d8cc0474ceb8.png)
### Analysis of Outcomes Based on Goals
Here we will look at outcomes based on the predetermined goal amount. Using the countifs function, sum function, and a basic percentage calculation I built a table that describes the number of successful, failed, and canceled campaigns based a goal amount.
![Outcome_Based_on_Goal_Table](https://user-images.githubusercontent.com/111163264/187096048-1386df57-a15f-4004-95fe-31335e347ce6.PNG)
Pulling from the data in the table, I inserted a line chart to improve our understanding the information.
![Outcomes_vs_Goals_Improved](https://user-images.githubusercontent.com/111163264/187096305-3b65b83e-d0d1-4b35-8fe7-c384188882a6.png)
### Challenges and Difficulties
One challenge faced was the grouping of the "Rows Labels" column. It took a little trial and error to get the grouping correct.
## Results
There are a couple of conclusions that can be drawn from the analysis of outcomes vs launch date. Firstly, failure rate remains relitively consistant throughout the year. That is to say, the month in which the play is launched doesn't seem to affect the failure rate. Secondly, summer is the season for successful theater campaigns. There is a high percentage of sucessful during these months. May is the clear winner with 111 successful plays vs 52 failures. 
The analysis of outcomes based on goals yeilds some interesting insights. The highest success rates are achieved when the goal is lower. There is, roughly, a 75% success rate for campaigns in which the goal is less than $5,000. However, there is a window of success for campaigns with goals between $35,000 and $49,999. 
There are limitations that must be addressed. We are analyzing art in connection with fund raising. Who are the fund raisers? Knowing who was organizing and leading these campaigns and what their marketing efforts looked like would help us better understand why particular campaigns are successful or not.
Combining the two analyzes above may lead to further insight. It would be interesting to look at when the campaigns with goals between $35,000 and $49,999 took place in the year. Calculating the percentage of successful vs failed campaigns in the outcomes based on launch date portion of the analysis would be helpful.
