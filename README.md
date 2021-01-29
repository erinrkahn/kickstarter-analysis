# Kickstarter Campaign Analysis 

## Overview of Project

### Purpose
The purpose of this analysis is to provide Louise, the client, with a clear picture of how Kickstarter campaigns have performed based on Launch Data and fundraising Goal amount, prompted by her recent Kickstarter campaign for the play, *Fever*. This analysis highlights how the Kickstarter Launch Date, specifically the month, has historically impacted the success (or failure) of campaigns in the "Theater" category and the potential relationship between Goal amount and resulting outcome in the subcategory "Plays". 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This analysis looked at the outcomes of Kickstarter campaigns in the "Theater" category over the years 2014-2016. The outcome counts (success, failure and canceled) have been tracked per month over 3 years. The highest counts of success were recorded in May (111), June (100) and July (87). The highest count of failed campaigns were recorded in May (52), July (50) and October (50). In December, succesful (37) and failed (35) campaigns were almost equal. Canceled campaigns had the highest count in Janaury and no campaigns were canceled in October.

#### Theater Outcomes vs Launch Date Graph
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/77405273/106233651-da051480-61ab-11eb-8492-9e6f7072ce20.png)

### Analysis of Outcomes Based on Goals
The analysis of outcomes based on goals was completed for the subcategory "plays" at increments of $5,000. The highest success rate is observed with campaigns that had goals below $5,000 (73-76%). The next highest success rate (67%) what observed in campaigns that had a goal that was greater than $35,000 and less than $50,000. Campaigns succeeded and failed equally (50%) in the $15,000-$20,000 range. The failure rate was 100% for campaigns in the $45,000-$50,000 range. The next highest failure rate is observed in the $25,000-$30,000 range at 80%. 

#### Play Outcomes Based on Goal Graph
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/77405273/106234020-bee6d480-61ac-11eb-819d-7d1c6c8f9adb.png)

### Challenges and Difficulties Encountered
I experienced challenges when completing the "Outcomes Based on Goals Analysis". I was unclear on how to define the amount range, but was able to come to a conclusion. While I was able to confirm I was receiving the correct output, I am not sure I have included the range in the most succinct way. Additionally, when I first tried to copy the formula from column B to use in column C, I wasn't aware that I needed the $ sign to "fix" which column the data was being pulled from, but was able to resolve this quickly. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - Kickstarter campaigns that were launched in late spring/early summer (May/June) exhibited higher rates of success than other months (111 and 100 campaigns respectively).
  - Campaigns launched in December almost equally succeeded (37 campaigns) and failed (35 campaigns). It is not recommedned to launch a campaign during this month.

- What can you conclude about the Outcomes based on Goals?
  - Campaigns that had a goal less than $5000 had the highest rate of success (73-76%) and campaigns with goals greater than $35,000, but less than $45,000 demonstrated the next highest success rate at 67%.

- What are some limitations of this dataset?
  - We could have removed some of the outlying goals that were much higher that the majority of Kickstarter campaigns to hone in on more accurate success metrics for Louise. 
   - In the "Outcomes Based on Goals Analysis", the graph can be misleading for the higher amounts because the dataset is so small. For example in the $40,000 to $50,000 range. 
   - Including both count and percent in both graphs would provide an extra layer of clarity for successful and unsuccessful campaign.
   - Data that represents more recent theater campaigns would be beneficial to our recommendations for Louise. 

- What are some other possible tables and/or graphs that we could create?
 
  - It would be helpful to include a percentage overlay on the "Theater Outcomes Based on Launch Date" graph as the comparison between successful and unsuccessful campaigns can visually be misleading. For example, March and August had a similar ratio of successful campaigns to failed campaigns, but because the graph exhibits a higher count of successful campaigns in August it appears to be a more adventageous month to launch vs March, which may not be the case. Conversely, a count overlay would be helpful on the "Outcomes Based on Goal" graph to add perspective to some of the percentages that are based on very few counts. 
  - We could provide Lousie with a graph that exhibited the percentage of failed "play" campaigns within each $5,000 increment where the pledge came within 10% of its goal. Instead of grouping all failed campaigns, we might find that in one range, most failed campaigns came quite close to their goal. This would provide an added layer of clarity for Louise in choosing a goal amount. 
  - Providing Lousie with a table of the average donation amount per $5,000 goal increment would better define what amounts to choose for the offers or incentived within her campaign.
  
  
