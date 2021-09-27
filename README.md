# Kickstarter-Statistics


## Overview

  I have performed analysis on kickstarter data to find any trends that could make a kickstarter campaign more successful, in this we focused on theater data. This was done by creating visualizations to find trends based off of start date and fundraising goal. 

## Analysis

###### Start Date Vs Success

  This Analysis looked in depth into different kickstarter campaigns that started between 2009 and 2017, with a focus on campaigns in the theater category. The first steps taken to look for patterns in the data was compare the data by timeframe to see if theater campaigns had been more or less successful durring specific times in the year.
  The first problem we ran into with this is we had to get readable dates for all the campaigns and the dates given to us with the data were in unix time. To fix this issue we had to first plug in a formula that would change it from time since epoch to the epoch of the human calendar, and then we were able to use the date function in excel to do the rest. 
  After getting readable dates we were able to create a pivot table that would produce the graph shown below.
  
![image](https://github.com/JonLev03-hub/Kickstarter-Statistics/blob/main/Theater%20Outcome%20Vs%20Launch.png) 

  This graph only shows the success rate for theater campaigns, and as you see to get the most successful campaign you would want to start the campaign between april and june. This would allow for the highest success rate for the campaign. You can also conclude that you should avoid starting campaigns in the winter if possible because they have an extremely low success rate; this is the only point of the year where there are almost more failed campaigns than successful campaigns. 
  
  ###### Goal Vs Success
  
  When thinking of other ways that we may be able to increase the success rate of a kickstarter campaign we looked into how the goal of the campaign may effect the success of the campaign. First we found some descriptive statistics around the campaign goals. We found that the campaigns with a lower goal tend to me more successful, the exact numbers are listed below 

![image](https://user-images.githubusercontent.com/81537476/134839345-e60d6a16-a5e2-4feb-ac5c-06e9ffb96fce.png)

  For a more in depth look we then created a chart that shows the percentage of successful, failed, and canceled campaigns at different goal ranges. In creating this we had run into issues reguarding syntax but after those were accounted for the chart was very streight forward to create. This chart is shown below.

![image](https://raw.githubusercontent.com/JonLev03-hub/Kickstarter-Statistics/main/Outcomes%20Vs%20Goals.png)

  When looking at this chart you will see that there is a clear negitive correlation between a campaigns goal and their success. 

## Conclusion

  After looking at all this data it is clear that if you would like to maximize a theater campaigns success you should ensure that it is launched in the summer and has a lower goal if possible, also ensure that it is not launched in the winter. It seems campaigns with these attributes have the highest success rate. This analysis does have some faults as the most recent campaign in the dataset was from 2019, so these numbers could have changed in the last two years. For further analysis it would be smart to dive deeper into the success of campaigns based off of goal specifically in the theater category. This could produce different results, as they might have a different standard. 

