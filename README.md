# An analysis of Kickstarter Campaigns
Performing analysis on kickstarter data to uncover trends

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
