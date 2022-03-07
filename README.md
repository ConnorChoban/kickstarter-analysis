# Kickstarting with Excel

Overview of Project

Our client Louise has started a Kickstarter campaign in order to raise funds to produce her play. She's tasked us with compiling data about preexisting kickstarter campaigns in order to provide insights into which factors affect whether a campaign is successful or not. By analyzing the launch date of each campaign and their respective funding goals, we can make several recommendations to Louise.

#Purpose

Evaluate the correlation between the launch date of a kickstarter and its success rate, as well as determining which funding goal is likely to be the most acheivable for Louise.

#Analysis and Challenges

We began our analysis by pulling data about a wide variety of Kickstarter campaigns and filtering by categories such as "Outcomes", "Country", and "Subcategory" to create a data range that's relevant to us. Then we furthered our analysis by creating two PivotTables and their corresponding PivotCharts to allow us to visualize the data in a more acessible format. Finally, we filtered our charts further in order to bring the most important data into focus.

#Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/99847786/156955906-ead1567f-0df6-4dc9-b86d-0b469aee3279.png)

We created a PivotTable using the variables "Outcomes" and "Date Created" to determine the correlation between the time of the year and a play's potential for success. By looking at both the table and the corresponding chart, we see that there was a moderate amount of fundraising campaigns at the beginning of the year, with the total amount of successful plays peaking in May and slowly decreasing throughtout the rest of the year. Conversely, we can see that the amount of campaigns that failed to reach their intended goal remained relatively stable throughout the year, with fluctuations around September and November. The amount of campaigns that were canceled remained very low, the maximum being 7 in January, and oscillating between 1 and 4 campaigns per month. The spread between "Successful" and "Failed" campaigns is greatest around May, likely due to the high volume of campaigns during this time but may be due to other factors. 

#Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99847786/156955853-580b5938-03b5-4bad-807f-9aae96a71656.png)

To visualize the relationship between a campaign's funding goal and it's success rate, we also created a PivotTable and corresponding chart. We can see that there's a negative correlation between the amount of funds requested and the success rate, where the higher of a fundraising goal that a campaign has the less likely it is to succeed, with one noticeable exception. Beginning in the range of 30,000 to 34,999 we see that the success rate begins to significantly increase, peaking in between the ranges of 35,000 to 39,999 and 40,000 to 44,999. The success rate then drops down to 0 for the range of 45,000 to 49,999, with some successful campaigns in the 50,000 and above range. 

#Challenges and Difficulties Encountered

This was a fairly simple analysis using a preexisting data set, so we didn't have to worry too much about collecting data since the information was readily available on Kickstarter's platform. Some potential challenges that could arise might be the aforementioned data collection process, determining which factors are relevant and provide the most information versus which factors are superfluous and are unhelpful to our analysis, and whether the date is accurate and trustworthy or not, which would impact our rate of confidence. 

#Results

We can draw several conclusions from analyzing the data in our PivotTables and PivotCharts. By looking at the chart for Outcomes Based on Launch Date, we can conclude that a fundraising campaign under theater subcategory is most likely to successful around May, June, and July; on the other hand, we can also see that a campaign is least likely to be successful towards November and December. Therefore, Louise's campaign would have the greatest chances of success if it were launched in May, with the chances of success decreasing as the year progresses. Alternatively, as there's a "bump" in the amount of successful campaigns during the month of February, with a mild increase of failed campaigns, there's also a noticeable spread. Louise could potentially launch her campaign then if she's not able to do so during the Spring/Summer months. 

Looking at the Outcomes Based on Goals charts and graphs, we can deduce that as a fundraising campaign's goal rises, the chances of it being successful are lower. As such, Louise should try to keep expenses as low as possible and produce a lower budget play if she's able to. On the other hand, she could launch the campaign with a goal in between 35,000 and 44,999, as there is also a greater chance of the play being successful (around 75%). She should be careful, though, not to exceed 45000 or more as in this range the chance of failure is 100%, based on given data. A greater budget might actually stir up interest in the play and convince attendees that the play will be a high quality production. 

#Limitations

For the Outcomes Based on Launch Date, I noticed that the only factor that we were able to visualize that had an impact on the success rate of a campaign was the time of year, but there's no explanation given for why a campaign is more successful during the Spring/Summer; we're left to deduce why on our own. Similarly, for the Outcomes Based on Goals, we see an increase in rate of a campaign's success in the 35,000 to 44,999 range but we don't have any other factors to explain why. 

#Additional Graphs

We could potentially use a bar chart to show the date for both outcomes, as well as a histogram. I would only recommend using a pie chart for the data set under Outcomes Based on Launch Date per month (ex. the amount of failed, successful, or canceled campaigns per month). Otherwise there's too many factors and the pie chart would likely be illegible or difficult to read.


