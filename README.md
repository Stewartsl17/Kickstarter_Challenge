# Kickstarter_Challenge

## Overview of Project 

Our client, Louise, has recently completed her Kickstarter campaign for the play, Fever, which she will be putting on in the UK. She asked us to looking into relevant Kickstarter data in order to glean insights from the data and advise her of the following information: 

  *Best approaches to successfully raising money for Kickstarter campaigns <br />
  *How different campaigns fared in comparison to their launch dates and funding goals in comparison to her campaign

## Analysis and Challenges

### Analysis Based On Launch Date 

In order to examine the best times of year to launch a theater-related Kickstarter campaign, we created a pivot table to look at campaign outcomes (successful, failed, and canceled) versus month from 2011 to 2017 among the Parent Category of theater. This analysis can been seen in the chart below labeled “Theater Outcomes Based on Launch Date”: 

![](https://github.com/Stewartsl17/Kickstarter_Challenge/blob/master/resources/Theater%20Outcomes%20vs.%20Launch.png)

On the x-axis, we have the each month of the year (Jan to Dec). On the y-axis, we have number of theater campaigns. We also have three lines referring to the three types of campaigns analyzed: orange (successful), yellow (failed), and green (canceled).

Using the graph, we can see the least amount of successful campaigns occur in December. On the other hand, we can note that February and, to a far larger degree, May, are the points of most success for theater campaigns.  

### Analysis Based on Goals

In order to observe differences in funding goals, we created a chart which looked at the following variables: goal amount, number of successful campaigns, number of failed campaigns, number of canceled campaigns, total projects, percentage successful, percentage failed, and percentage canceled. For goal amounts, we split the goal amounts into 12 distinct increments ranging from less than $1,000 to $50,000 or greater. The analysis can been in the chart below labeled “Outcomes Based on Goals” 

![](https://github.com/Stewartsl17/Kickstarter_Challenge/blob/master/resources/Outcomes%20vs.%20Goals.png)

On the x-axis, we have the goal amount increments ranging from less than $1,000 to $50,000 or greater. On the y-axis, we have percentage buckets from 0 to 100%. 

Using this graph we can see that the most successful campaigns occur for less than $5000. This is understandable as the cost is still relatively low. Another interesting section is between $35,000 and $49,999. 

### Challenges

Overall, there were not many issues with the data set that we used to conduct our analysis for Louise. The first challenge of the data was that some projects couldn't be initally utilized because of the lack of backers for some campaigns despite every campaign having a goal. This led to the data set having errors, which we had to convert to zeros. The second challenge that we encountered while doing analysis was having to do multiple transfomations for different columns of data. In order to specifically look at plays, we had to seperate the parent category (Theater) from the subcategory (plays). Furthermore, in order to look at the correct dates of campaign launches, which we intitally formatted as Unix timestamps, we had to convert them into human-readable dates. Also, to inspect look further into dates grouped into months, we had to convert launched dates into months using the month formula. 

### Conclusions based on Launch Data 

Based on the launch date data that was analyzed, we can conclude the following: 

* Starting a Kickstarter campaign for theater-related events in May has the widest margin of success, followed by February. 
* Conversely, starting a campaign in Decemeber has the highest chance of failure. 

### Conclusions based on Goals 

Based on the goals data that was analyzed, we can conclude the following: 

* Starting a Kickstarter campaign for plays with the goal amount of less than $5000 will lead to the most successful outcomes followed by between $35,000 and $49,999 to a lesser degree. Overall, Louise should bring her goal amount down to the optimal range of less than $5000 if she wants to have the highest chance of success in future campaigns. 

## Limitations of Dataset

Overall, the dataset was fairly complete but there were a couple limitations that could provide insight for future analysis: 

* One limitation of the dataset is lacked on variables to analyze in terms of impact on success and failure. There was no way to look into amount of outside work (promotions and other awareness-related work) that led to successful, failed, or canceled campaigns. 
* Moreover, all of the data was in US currency so we did not look into the changes between different currencies. This could provide some interesting insights as well as could change when looking individual factors by countries. 

## Other possible tables or graphs 
