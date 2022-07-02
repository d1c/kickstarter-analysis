# Kickstarting with Excel

## Overview of Project
[Kickstarter](https://www.kickstarter.com/) is a crowdfunding website that allows people with project ideas to raise funds to bring their project to fruition. Without Kickstarter many of these projects would not see the light of day due to the lack of funds to develop the projects. Projects range from self published books and games to theater projects and technology projects.

### Purpose
A client recently ran a Kickstarter campaign to raise funds for their theatrical play "Fever." The client has asked for analysis of Kickstarter data to provide insight into the relationship of a campaigns launch date and funding goals to successful funding. Using Microsoft Excel, data from over 4,000 Kickstarter campaigns is analyzed to provide the client with recommendations.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Looking at the Outcomes Based on Launch Date chart below, we see that failed campaigns remain relatively flat throughout the year between a range of 31 and 52. However, there is more variation to the month to month trend for successfull campaigns. In January, successful campaigns begin the year at 56 rising to a high of 111. Through the rest of the year, the number of successful campaigns declines to a low of 37 in December.

![Launch Date Outcomes Chart](/Resources/Theater_Outcomes_vs_Launch_Date.png)

### Analysis of Outcomes Based on Goals
Moving to the Outcomes Based on Goals analysis, rather than looking at a time series of data we placed the data into 12 separate buckets. With the exception of the highest and lowest buckets we placed the data into $5,000 increments. In the highest bucket we placed any campaign with a goal greater than $50,000 and in the lowest bucket we placed any with a goal of less than $1,000.

![Outcomes vs. Goals Chart](/Resources/Outcomes_vs_Goals.png)

As you can see in the chart, the trend in this chart is less consistent than the trend seen in the Launch Data analysis above. The success and failed trend lines flip back and forth a few times. In general, those campaigns with goals less than $15,000 have been more successful than those campaigns with higher goals. The exception to this observation are those campaigns with goals between $35,000 and $45,000. 

### Challenges and Difficulties Encountered

Challenge for the Goals based Outcome - less data at the higher amount goals makes it difficult to have confidence in the higher success outcomes in the $35,000 - $45,000 buckets. For comparison, there were only 26 total projects in the four buckets above $35,000 while there were 1,032 total projects in the four buckets lower than $15,000.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. The best time of the year to launch a Kickstarter campaign is in the middle half of the year between April and August.
  2. January through March along with September would be good second choices. 
  3. However, October through December should be avoided since the gap between Failure and Success narrows until the gap virtually disappearsin December.

- What can you conclude about the Outcomes based on Goals?
  1. In the theatrical plays subcategory, it would be best to keep the fundraising goal to less than $15,000. From $15,000 going down the success rate increases so lower would be better to increase the liklihood of success.

- What are some limitations of this dataset?
  1. As stated in the analysis above, confidence in the higher amount ranges for the Outcomes based on Goals chart is not high based on fewer total projects with a goal higher than $20,000.
  2. Age of the data could be a limitation. The latest date in the dataset is from 2017. More recent trends could be significantly different in 2022 vs five years ago.
  3. Marketing or word of mouth awareness plays a big role in the success or failure of any fundraising effort. With this data, we cannot measure or analyze what efforts the project owners took to increase awareness of their project.
  4. Rewards are another factor that can motivate donors to give money to support a Kickstarter project. In this dataset, there were no measure of rewards offered.

- What are some other possible tables and/or graphs that we could create?
  1. If data were available, it would be good to see how many visitors viewed each project.


