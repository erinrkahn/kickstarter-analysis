# Kickstarter Campaign Analysis 

## Overview of Project

### Purpose
The purpose of this analysis is to provide Louise, the client, with a clear picture of how Kickstarter campaigns have performed based on Launch Data and fundraising Goal amount, prompted by her recent Kickstarter campaign for the play, *Fever*. This analysis highlights how the Kickstarter Launch Date, specifically the month, has historically impacted the success (or failure) of campaigns in the "Theater" category and the potential relationship between Goal amount and resulting outcome in the subcategory "Plays". 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This analysis looked at the outcomes of Kickstarter campaigns in the "Theater" category over the years 2014-2016. The outcome counts (success, failure and canceled) have been tracked per month over 3 years. The highest counts of success were recorded in May (111), June (100) and July (87). The highest count of failed campaigns were recorded in May (52), July (50) and October (50), and in December, succesful (37) and failed (35) campaigns were almost equal. Canceled campaigns had the highest count in Janaury and no campaigns were canceled in October.

#### Theater Outcomes vs Launch Date Graph
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/77405273/106233651-da051480-61ab-11eb-8492-9e6f7072ce20.png)

### Analysis of Outcomes Based on Goals
  - Highest less than 5000
  - 35000 to <50000 next (67%)
  - equal at 15000-<20000 
  Failure peaked at 45,000-<50,000 (100%)
  next failure 25,000<30,000 (80%)

#### Play Outcomes Based on Goal Graph
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/77405273/106234020-bee6d480-61ac-11eb-819d-7d1c6c8f9adb.png)

### Challenges and Difficulties Encountered
  Range data, percentage choice

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - Kickstarter campaigns that were launched in late spring/early summer (May/June) exhibited higher rates of success than other months (111 and 100 campaigns respectively).
  - Campaigns launched in December almost equally succeeded (37 campaigns) and failed (35 campaigns). It is not recommedned to launch a campaign during this month.

- What can you conclude about the Outcomes based on Goals?
  - Campaigns that had a goal less than $5000 had the highest rate of success (73-76%) and campaigns with goals greater than $35,000, but less than $45,000 demonstrated the next highest success rate at 67%.
  - Campaigns with goals greater than *$25,000/less than $30,000* and *greater than $45,000/less than $50,000* experienced the highest percentages of failure.

- What are some limitations of this dataset?
  - outliers (big goals that were met), small numbers in $ categories, count vs percentage, year range vs. current, 

- What are some other possible tables and/or graphs that we could create?
 
  - It would be helpful to include a percentage overlay on the "Theater Outcomes Based on Launch Date" graph as the comparison between successful and failed campaigns can visually be misleading. For example, March and August had a similar ratio of successful campaigns to failed campaigns, but because the graph exhibits a higher count of successful campaigns in August it appears to be a more adventageous month to launch vs March, which may not be the case. Conversely, a count overlay would be helpful on the "Outcomes Based on Goal" graph to add perspective to some of the percentages that are based on very few counts. 
  
  
