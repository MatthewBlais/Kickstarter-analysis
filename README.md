# An Analysis of Kickstarter Campaigns
#### 1. Overview of Project

Louise has begun raising money for her play _Fever_ and is close to meeting her fundraising goal on Kickstarter. My goal is to analyze and interperet data from Kickstarter for Louise to help her understand any relationship between the succsess rate of previous campaigns and both their launch dates and funding goals. 

#### 2. Analysis and Challenges

I began this analysis by creating a pivot table out of the Kickstarter data. This table broke down how many Kickstarters under the Parent Category Theater were successful, failed, and canceled between the years 2016 - 2014. See Screenshot of table below.

https://github.com/MatthewBlais/Kickstarter-analysis/blob/main/Crowd%20funding%20analysis/resources/PivotTable.png

In order to better represent this data a line chart was added. This is a better visual representations of how Theater kickstarters preformed over each different month. See Screenchot of Chart below.

https://github.com/MatthewBlais/Kickstarter-analysis/blob/main/Crowd%20funding%20analysis/resources/Theater_Outcomes_vs_Launch.png

Louise was also interested in the relationship between success rate and funding goals. The Kickstarter data was broken down into rows by Goal amount, and coulmns by succsseful, failed, and canceled. Using the =countifs function, I was able to determine based off of goal parameters how many kickstarters were successful, failed, and canceled. I then used the =sum function to create a total projects coulmn. I then was able to find percentage of successful, failed, and canceled projects. See Screenchot of table below.

https://github.com/MatthewBlais/Kickstarter-analysis/blob/main/Crowd%20funding%20analysis/resources/Table_of_Outcomes_by_Goal_Amount.png

Again a line chart was added to provide a better visual representation. This chart shows the outcomes based on goals. See Screenshot of Chart below.

https://github.com/MatthewBlais/Kickstarter-analysis/blob/main/Crowd%20funding%20analysis/resources/Outcomes_VS_Goals.png

Some of the challenges in this analysis was that live kickstarters were removed from the analysis. It did not make sense to keep them in as we are not sure if they will become succssesful campaigns or not. Using filters on the PivotTable and =countifs functions these kickstarters are not being included in the analysis.

#### 3. Results

##### Conclusions of Theater Outcomes by Launch Date

It can be concluded that May is the most succsesfull month to launch a theather kikckstarter, holding all other variables the same. From the years of 2014-2016 in the month of May 111 out of 166 theater kickstarters were succsesful. Only 52 failed while 3 were canceled. This is also the month that had the most total kickstarters attempted, so a largest sample had the most succsesful rate outcome. We can also conclude that December was the worst month to launch a theather kickstarter. 37 out of 75 December campaigns were successful, while 35 failed and 3 canceled. This is the only month where the total of failed and canceled campaigns was greater than the amount of succsesful campaigns.

##### Conclusions of Outcomes based on Goals

It can be concluded that Based on percentage of outcomes campaigns with a goal of less than $1,000 were the most likely to be successful. It also shows that goals grater than $50,000 were the most likely to fail. It is not a complete negetaive corilation, but it can be assumed that the more one is going to request as a goal the less likely it will be succsesful.


