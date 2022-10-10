# Kickstarting with Excel

## Overview of Project
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset that you’ve already combed through, you’ll visualize campaign outcomes based on their launch dates and their funding goals. You’ll then submit a written report based on your analysis and the visualizations you create.
### Purpose
The Purpose of this project is to analyze a crowd sourcing spreadsheet which includes data for several funding campaigns for various projects including Films, Music, and Photography. The Data also includes information on the dollar amount for the campaign Goals and the actual amount Pledged. We will also be looking at Successful and Failed campaigns and launch dates of the campaign.  Particularly, we want to look at Louise's play "Fever" compared to other campaigns and how well they did. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For Louise's Play, we know that the play made $2485.00 in pledges which did not meet the goal of $2885.00, the campaign was launched in June 2016, the play was under the "Theater" category, and the outcome was "failed". Our first attempt at analysis is to look at all Theater campaigns, Success,  Failure or Canceled, based on the launch dates to see how Louise's play "Fever" compares. To do this, a Pivot Table was made that grouped the months with the number of outcomes broken out by, Success, Failed and Canceled with filters for Category and Year. 

![This is an image](https://github.com/chsaporito/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

When we filter by "Theater", we see the highest number of success's is in the month of May with a count of 111, followed by June with a count of 100. We can also see that May also has the highest number of Failed campaigns as well, but the trend is relatively flat for June and July.  We can also see that Successful and Failed follow a similar trend, but this appears to be a function of the total number of campaigns where there are simply more campaigns in May followed by June and so on.  So, the more campaigns there are, the more successful campaigns and the more failed campaigns you will see. Canceled campaigns vary from a count of 0 to 7 campaigns with no trend.

For this analysis, Louise's play failed to meet its goal along with 48 other campaigns under the Theater category where 100 campaigns succeeded.  

### Analysis of Outcomes Based on Goals
![This is an image](https://github.com/chsaporito/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
