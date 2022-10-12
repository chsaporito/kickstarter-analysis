# Kickstarting with Excel

## Overview of Project
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset that you’ve already combed through, you’ll visualize campaign outcomes based on their launch dates and their funding goals. You’ll then submit a written report based on your analysis and the visualizations you create.
### Purpose
The Purpose of this project is to analyze a crowd sourcing spreadsheet which includes data for several funding campaigns for various projects including Films, Music, and Photography. The Data also includes information on the dollar amount for the campaign Goals and the actual amount Pledged. We will also be looking at Successful and Failed campaigns and launch dates of the campaign.  Particularly, we want to look at Louise's play "Fever" compared to other campaigns and how well they did. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For Louise's Play, we know that the play made $2485.00 in pledges which did not meet the goal of $2885.00, the campaign was launched in June 2016, the play was under the "Theater" category, and the outcome was "failed". Our first attempt at analysis is to look at all Theater campaigns, Success,  Failure or Canceled, based on the launch dates to see how Louise's play "Fever" compares. To do this, a Pivot Table was made that grouped the months with the number of outcomes broken out by, Success, Failed and Canceled with filters for Category and Year. We then created a Line Chart to visualize the data.

![This is an image](https://github.com/chsaporito/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
For the next analisys, a table was created with 12 ranges of values to group the goal amount.  Each grouping showed the number of Successful, Failed and Canceled outcomes along with the totals for each grouping and the percentages of successful, failed and canceled outcomes per grouping. The Excel function function "countifs" was used to extract the goal numbers based on the ranges of dollar amount.
A line chart was used to show how each outcome fared based on it percentage.
![This is an image](https://github.com/chsaporito/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. When we filtered by "Theater", we see the highest number of success's is in the month of May with a count of 111, followed by June with a count of 100. We can also see that May also has the highest number of Failed campaigns as well, but the trend is relatively flat for June and July.  We can also see that Successful and Failed follow a similar trend, but this appears to be a function of the total number of campaigns where there are simply more campaigns in May followed by June and so on.  So, the more campaigns there are, the more successful campaigns and the more failed campaigns you will see.
2. Louise's play failed to meet its goal along with 48 other campaigns under the Theater category where 100 campaigns succeeded.

- What can you conclude about the Outcomes based on Goals?
Failed campaigns with a goal amount of less than $1000 failed less than ~30% of the time. Failures increase steadily as as the goal amount increases until it peaks at an 80% failure rate with goals between $25,000 and $29,999. This would suggest that Goals set at a higher amount fail more often. We can see that this trend does not hold after the $35,000 to $39,999 range but this is certaily due to the low number of project counts of 6 and 3 at these ranges. Failures at the $45,000 to $49,999 spike 100% but there is only 1 project that this number is based on.  Projects at $50,000 or more, of which there are 16, continues the trend up for failures. Conlusion is that higher goal amounts will result in more failures but more data is needed.
![image](https://user-images.githubusercontent.com/110853496/195449590-84ecb3da-eb6d-4e5a-8cbd-1661689634a6.png)

![image](https://user-images.githubusercontent.com/110853496/195449277-8a7a990a-b81b-42db-b073-f6f615896442.png)

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
