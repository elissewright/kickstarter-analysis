# **Analysis of Kickstarter Data** 

## **Overview of Project**

### This data analysis was performed in order to help a client understand how well various Kickstarter campaigns performed, in regards to funding plays and other entertainment endeavors. We evaluated several theater performances, including launch dates, funding goals, and final outcomes, performing statistical operations to produce effect measures and visual representations of our analyses. 

## **Analysis and Challenges** 

### We first analyzed outcomes for the theater category, on the basis of launch date. The first significant challenge was posed by the vast size of the data contained within the spreadsheet, as well as the amount of extraneous data included that was not relevant to our goals. We needed to narrow down the data we would analyze by focusing on a few categories and variables. In order to do this, we used an Excel spreadsheet to create two new variables for the category variable, which made it possible to apply filters and analyze funding goals, funding pledged, launch and end dates, and final outcomes for all titles in the theater category alone. A pivot chart was created in order to reference the outcomes of all theater campaigns based on launch date by year, and a visual representation of findings was created the form of a [line graph](https://github.com/elissewright/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png).  

### Our secondary goal was to further analyze data related to funding and outcomes of plays in particular, in order to assess the proportion which succeeded, failed, or were canceled. Again, we faced the challenge of narrowing down data to the desired specifications; to do this, the theater category was further filtered into a subcategory of plays. We created another pivot chart, this time looking at the outcomes of plays, based on initial funding goals. In order to better display the results of this analysis, we transformed "funding goal" into a discrete variable by creating categories of $5000 increments and using COUNTIFS statements in order to sort the data for plays into the appropriate funding category. We used a combination of the SUM variable, as well as some constructed equation codes to evaluate the proportion of plays that fell into each funding category, based on the final outcome. This data was also represented visually in a [line graph](https://github.com/elissewright/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png). 

## **Results** 

### We can conclude that May appears to be the most successful month for theater performances funded by Kickstarter campaigns, followed by June and July; the winter months from November-January appear to be a less successful timeframe. We can also conclude that the number of failed and cancelled plays are more consistent and stable over time, but are fewer in number overall than successful campaigns. 
  
### We cannot infer causality from this data, but one potential factor influencing outcomes for successful endeavors may be that people have more free time or disposable income to donate to a campaign in the summer, as opposed to near winter holidays. This may be an interesting topic to further evaluate in future analyses or studies. 

### In terms of Outcomes based on Goals, we can conclude that titles in the plays subcategory were cancelled as an outcome. Our analysis suggests that, other that a few exceptions in the $35,000-$45,000 range, it appears that successful outcomes are more likely for plays with smaller funding goals, and likely to fail with increasing size of funding goal. Campaigns with goals to raise $25,000 or more in particular appear to be very unlikely to succeed. 

## **Discussion and Limitations**

### One limitation of the analysis of theater outcomes by launch date is that we did not include other factors and variables in the pivot table, some of which may have influenced the outcome. For example, including the funding goal as an additional filter may have revealed the distribution over time of theater campaigns with small and large goals.

### A major limitation of our second analysis was that it did not include an assessment of potential outliers and the impacts they may have on the results. An outlier may skew data analysis in misleading ways, and may need to be removed from the data set under certain circumstances. There is a possibility that some or all of the few successful plays with funding goals at or above $35,000 may be outliers that could be investigated and possibly removed from the data set prior to analyses. 

### Other limitations include a lack of evaluation of other meaningful effect measures and statistical significance tests, and limited visual representations of data, which could have been expanded by including additional types of graphs. 

### Another graph that could provide some additional data is a box and whisker plot, which would give us a quick visual reference to any potential outliers in the data set. If desired, we could also do additional statistical analyses to formally evaluate outliers, as well as effect measures like standard deviation and statistical significance. 
