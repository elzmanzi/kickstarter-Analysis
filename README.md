# kickstarter-Analysis
## Overview of Project
In this project, we will performing Analysis on Kickstarter data from 2009 to 2017 to determine whether there is some factors that detemines a campaign to be successful or fail. we will focus on  the category of theater, it's outcomes based on launch date and plays subcategory.   

### Purpose

This project is about a crowdfunding project. We will analyze compaigns outcomes comparing to innitial goal funding and launch dates. 
In the dataset we will mainly focus on Theater category, it's outcomes based on launch date. 
In the same Theater category we will look at  subcategory of plays and analyse it's outcomes based on goal. 

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
- Outcomes based on launch date graph shown below is  that the best months to launch campaigns are starting from April to July, it appears to be a good season for plays. 
- The month December is not the good month at all, the number of successfull campaign is almost equal to the failed ones. 
![Theater outcomes based on launch date](https://github.com/elzmanzi/kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
- By comparing those failed and successful using central tendancy measures, i found that mean of failed is almost twice as the successful ones,
- There is a huge difference  between mean and median for both failed and successful campaign, this might be in the high increase in goal value. 
- the third quartile is almost similar to mean, which may suggest that data follows the same distributions 
- on the Failied kickstarter the standard deviation is almost three times compairing to the IQR, which maybe high goal money could be the potential issue of failing. 
![Outcomes based on goal](https://github.com/elzmanzi/kickstarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

- The difficulties i encountered in this dataset is to make sure the data provided are in the right formats, for example I had to convert deadline and launched unix timestamp format  into dates format. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    - In the Outcomes based on launch date, I noticed that April to July are best time of launching campaigns.  
    - The month of May is where we have success rate comparing to the rest of the months of the year. 

- What can you conclude about the Outcomes based on Goals?

    - The Outcomes based on Goals, The data shows that as the price goal increases there is high chance that our campaign will fail.

- What are some limitations of this dataset?

The limitations about this data is that not only outcome based on date launched or goal will define the success of this campaigns, 
we will have to consider other aspects like which country we have a high successful rate. 
How much people are pledging to atteign our goal. How did they get to know this campaign, 

- What are some other possible tables and/or graphs that we could create?

- Possible graph that can help my analysis will be Box and Whisker plots to better determine my outliers,
 a column chart to determine which subcategories are performing better than others. 
 
- I will consider as well another pivot table to be able to filter countries for both category and subcategory
 so that i can analyze in which country we are having successful compaigns.

