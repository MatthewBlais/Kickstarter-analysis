# An Analysis of Kickstarter Campaigns
#### 1. Overview of Project

Louise has begun raising money for her play _Fever_ and is close to meeting her fundraising goal on Kickstarter. My goal is to analyze and interperet data from Kickstarter for Louise to help her understand any relationship between the succsess rate of previous campaigns and both their launch dates and funding goals. 

#### 2. Analysis and Challenges

I began this analysis by creating a pivot table out of the Kickstarter data. This table broke down how many Kickstarters under the Parent Category Theater were successful, failed, and canceled between the years 2016 - 2014. See Screenshot of table below.

https://github.com/MatthewBlais/Kickstarter-analysis/blob/main/Crowd%20funding%20analysis/resources/PivotTable.png

In order to better represent this data a line chart was added. This is a better visual representations of how Theater kickstarters preformed over each different month. See Screenchot of Chart below.

https://github.com/MatthewBlais/Kickstarter-analysis/blob/main/Crowd%20funding%20analysis/resources/Theater_Outcomes_vs_Launch.png

Louise was also interested in the relationship between success rate and funding goals. The Kickstarter data was broken down into rows by Goal amount, and coulmns by succsseful, failed, and canceled. Using the =countifs function, I was able to determine based off of goal parameters how many kickstarters were successful, failed, and canceled. I then used the =sum function to create a total projects coulmn. I then was able to find percentage of successful, failed, and canceled projects. See Screenchot of table below.

