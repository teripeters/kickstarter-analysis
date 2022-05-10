# Kickstarting with Excel

## Overview of Project
Louise would like to see the outcomes of Kickstarter campaigns in terms of launch dates and funding goals.

### Purpose
Demonstrate outcomes of Kickstarter campaigns based on launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I started by creating a pivot chart that shows outcomes (successful, failed, canceled) by month (January-February). Filtering the chart so that it only shows the theater category, shows that May, June, and July have the highest number of successful launches. Interestingly, those same months have the highest number of failed launches. There are about twice as many successful launches than failed in May-July. 

The line graph shows that there is a peak in successful launches in May, with smaller peaks in February and October. It also demonstrates that December has almost as many successful launches as failed launches. 


### Analysis of Outcomes Based on Goals
In order to analyze Kickstarter outcomes based on funding goals, we grouped outcomes within twelve ranges of funding goals: 
- Less than 1000
- 1000 to 4999
- 5000 to 9999
- 10000 to 14999
- 15000 to 19999
- 20000 to 24999
- 25000 to 29999
- 30000 to 34999
- 35000 to 39999
- 40000 to 44999
- 45000 to 49999
- 50000 or More

After grouping the funding goals according to the determined ranges and adding the columns for the number of successful, number of failed, number canceled, and total number of projects, we were able to use that information to determine the percentages of successful, failed, and canceled projects. 

A review of the chart shows that the highest number of successful campaigns according to funding goal is within the 1000 to 4999 range and the second highest is the Less than 1000 range. However, the line graph, which shows outcomes by percentage, demonstrates that projects with a funding goal less than 1000 have a 76% success rate, and projects with funding goals of 35000-39999 and 40000 to 44999 are tied for the second-highest success rate of 67%. 


### Challenges and Difficulties Encountered
There were no challenges or difficulties encountered in the analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. The best time to launch a theater campaign is May, June, or July when they are twice as likely to succeed as to fail.
2. Campaigns launched in December are just as likely to succeed as to fail.

- What can you conclude about the Outcomes based on Goals?
1. The failure rate equals or exceeds the success rate for campaigns with funding goals between 15000 to 34,999 and greater than 45,000. 
2. The greatest rate of success is for campaigns with a funding goal of less than 1000, with the second-highest success rate for goals between 35000 and 44999.

- What are some limitations of this dataset?
The dataset does not consider location, which could have a significant impact on results. 

- What are some other possible tables and/or graphs that we could create?
1. Add country as a filter to existing tables.
2. Line graph by year to see if there are any trends over time that could impact our analysis because we are assuming that the aggregated monthly totals reflect current conditions. 
3. Table that includes subcategory to get more specific data
