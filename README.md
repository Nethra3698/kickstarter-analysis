#An analysis of Kickstarter Campaigns

##Performing analysis on kickstarter data to uncover trends

The Kickstarter worksheet contains the data that is main point of analysis here. The data is collected to help Louise with a crowdfunding project. We are conducting further analysis on the data so that the data can be produced more neatly and clearly to Louise. 

Initially, the parent categories and subcategories were separated for clarity and a better depth into the data. On doing so, pivot tables and pivot charts for outcomes based on parent categories and outcomes and outcomes based on subcategories were derived. 
Figure 1 is the pivot chart for the outcomes based on the parent categories and Figure 2 is the pivot chart for the outcomes based on the subcategories.
![Figure 1. Parent Category Outcomes](https://github.com/Nethra3698/kickstarter-analysis/blob/master/ParentCategoriesOutcomes.PNG)
![Figure 2. Subcategory Outcomes](https://github.com/Nethra3698/kickstarter-analysis/blob/master/SubcategoryOutcomes.PNG)

The time was also concerted from Unix timestamps to MM/DD/YYYY format so that they can be used be used for analysis. Using these converted dates, a pivot table and pivot chart was formed for outcomes based on launch date which is represented in figure 3. 

![Figure3. Outcomes of Launch Date](https://github.com/Nethra3698/kickstarter-analysis/blob/master/OutcomesLaunchDate.PNG)

Next, in the Edinburgh research worksheet, we were able to consolidate all the essential data for the five plays that Louise saw in the Edinburgh festival and know how they were funded by using VLOOKUP without having to go through all the data. 

Finally, the Descriptive Statistics worksheet gives the essential statistical data for successful and failed US kickstarters. To do this, a  successful US kickstarter and failed US kickstarter worksheets were created and their mean, median, standard deviation and quartile ranges were obtained. On comparing the data, it can be seen that the Goal for the failed US kickstarters is much higher than the successful ones  while the pledged amount for the failed US kickstarters were very low. A box plot also shows this data analysis very clearly in the worksheet boxplot. 
![Figure4. Boxplot of goals and pledged of musicals in Great Britain](https://github.com/Nethra3698/kickstarter-analysis/blob/master/Boxplot.PNG)

##Challenge

The Outcome based on the goals worksheet and line graph compares the percentage successful, failed and canceled for each of the goal ranges. The graph represents a higher percentage of successful campaigns for a lower goal. As seen from the graph, the percentage for successful decreases with increase in goal. Similarly, the percentage failed increases with an increase in the goal. Since the plays subcategory is being considered here which doesn't have any cancelled campaigns, the percentage cancelled is 0 throughout. The percentage failed has a increasing trend with spikes as the goal increases and the percentage suceessful descreases with an increase in the goal. Looking at the trends, wherever the percentage successful is higher the percentage failed is lower. This shows that there might be goals that have a higher chance of success than others. In this case, that would be any value below $5,000, leaning towards a lower goal as the percentage successful is greater than 50% below this value.

[Figure5. Outcome based on goals](https://github.com/Nethra3698/kickstarter-analysis/blob/master/OutcomeBasedOnGoalsChallenge.PNG)

The Outcome based on Launch date worksheet and pivot chart plots the successes, failures and cancellations based on the months that the campaigns were launched. This particular chart looks at the theatre category. From the graph, it is clear that the months May, June and July are the best times to do the campaign and were the most successful while October and December werent good months to do them. 

[Figure6. Outcome based on Launch Date](https://github.com/Nethra3698/kickstarter-analysis/blob/master/OutcomeLaunchDateChallenge.PNG)

###Limitations of the Data/ Additional tables and Graphs

Here we want to know the relationship between the length of a campaign and how it contributes to its success and failure. The graphs that we have at hand only tells us about when the campaigns do the best and how many campaigns did well based on the goals. To find out how many were successful in a short amount of time we would have to create another graph that compares the outcome with the the time of the campaign as done in the figure below. This was done by generating the data for the time of the campaign and using countifs to create a similar worksheet to the Outcomes based on Goals one. A line graph was then created based on this data set. 

[Figure7. Outcome based on time of campaign](OutcomeBasedOnTimeOfCampaignChallenge.PNG)
