 Kickstarting with Excel

## Overview of Project
Louise is organizing a play called Fever. To fund the play Louise started a Kickstarter campaign. 
Louise's kickstarter campaign was not successful.

### Purpose
Louise would like to understand how different campaigns faired based on their launch dates and whether
they achieved their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The total number of Kickstarter campaigns has increased by over 660% since 2009. The largest Kickstarter category is Theater. 
Theater comprised over 40% of the total campaigns between 2014 and 2016. Theater's average success rate (successful campaigns / total campaigns)
since 2014 has been over 65% this is much higher than the success rate for non-theater campaigns which average 40%. 

Between 2014 and 2016, unsuccessful Kickstarter campaigns lasted on average 34.7 days whereas successful campaigns were finished nearly 3 days earlier (31.9 days)
The most successful month to launch a Kickstarter campaign is May and the worst month is December.

![outcomes_line_chart](https://github.com/ryanmorin/kickstarter_analysis/blob/main/Theater_Outcomes_vs_Launch.bmp?raw=true)

### Analysis of Outcomes Based on Goals
The average successful campaign ($9.8K) had a goal that was 6x's smaller compared to campaigns that were unsuccessful ($60K). Successful Theater campaigns had a goal that was 31% smaller compared to the average.  Unsuccessful theater campaigns had goals that were 9% larger than the average unsuccessful campaign. 

Campaigns that met their goals had a larger number of backers compared to unsuccessful campaigns.

![outcomes_line_chart](https://github.com/ryanmorin/kickstarter_analysis/blob/main/Outcomes_vs_Goals.bmp?raw=true)

### Challenges and Difficulties Encountered
If the staff pick field is "TRUE" the campaign has a much better chance of begin successful (87%) compared to those campaigns where that 
field is "FALSE" (47%). The same is true for the Spotlight field.  All campaigns (100%) where the field is "TRUE" were successful and 100% where the field was "FALSE" were unsuccessful. It's important to know how this is assigned as it seems to impact the likelyhood of a successful campaign.

The data set had an additional outcome descriptor: live.  This was not cited in the assignment instructions regardless I chose to keep the data in the data set. All the 'live' outcomes are found in 2017.  The findings outlined above generally refer to data between 2014 and 2016.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
   1. There was more chance of a successful outcome if a campaign was launched in May compared to December
   2. Shorter campaigns are more likely to have a successful outcome.

- What can you conclude about the Outcomes based on Goals?
   1. The smaller the goal, the greater the chance for the campaign to meet it's goal.
   2. The greater the number of backers, the greater the chance for the campaign to meet it's goal.

- What are some limitations of this dataset?
   1. The Staff Pick field isn't well understood. It seems to be closely associated with a successful campaign.
   2. The Spotlight field isn't well understood. It seems to be closely associated with a successful campaign.
   3. The data set had an additional outcome called 'live'.  I chose to keep the 'live' outcomes in the data set.
   
- What are some other possible tables and/or graphs that we could create?
   1. Success Rates by Month
   2. Average amount of time for a successful campaign
   3. Average amount of goal for successful campaigns vs. unsuccessful campaigns


[Kickstarter Challenge](https://github.com/ryanmorin/kickstarter_analysis/blob/main/kickstarter_challenge.zip)
