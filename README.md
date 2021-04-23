# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this kickstarter analysis was to compare how the fundraiser for Lousie's play _Fever_ performed compared to campaigns for other theater plays throughout the world. Specifically, we were calculating the outcomes of other theater campaigns based on both their start date and their financial goal amounts. By using these data, we can provide Louise with information about whether her campaign truly was successful and if it could have performed better using different criteria. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This analysis was performed using a PivotTable compiled from all "Kickstarter" campaign data and then filtered by the "Theater" parent category. These data were then grouped into the number of "Successful", "Failed", and "Canceled" campaigns in each of the 12 months of the years 2009-2017. We then created a PivotChart line graph to visually analyze these data and identify any trends. This graph ("Theater Outcomes Based on Launch Date") can be found in the "Resources" folder for this project.

![Image of Theater Outcomes vs Launch](https://github.com/jpb12002/kickstarter-analysis/blob/1804cef466efab64bdfc20a6c9b47daa422c68cd/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
This analysis was performed by creating a new worksheet in which the number of "Successful", "Failed", and "Canceled" of the "Kickstarter" campaign data were grouped by ranges of goal amounts (i.e., less than $1000, $1000 to $4999, etc.). The data was futher filtered to only include campaigns for the "Plays" subcategory. We then calculated the percentage of each outcome for the various goal amount ranges. A line graph was created to visually analyze these data calculations and identify any trends. This graph ("Outcomes Based on Goal") can be found in the "Resources" folder for this project.

![Image of Outcomes vs Goals](https://github.com/jpb12002/kickstarter-analysis/blob/1804cef466efab64bdfc20a6c9b47daa422c68cd/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
A challenge that was encountered during the "Outcomes Based on Launch Date" analysis was filtering the outcomes in the PivotTable from largest to smallest so that "Successful" outcomes were seen in the first column. I had to keep applying the "Sort Z to A" filter on various fields in the chart until I found the right combination to produce the expected result (applying the filter on the "Column Labels" cell in the chart).  

A challenge that was encountered during the "Outcomes Based on Goals" analysis was figuring out the appropriate formula to use so that "Percentage" format could be used in the corresponding sheet columns. Upon further research, it was discovered the "Percentage" format was automatically multiplying the result of each calculation by 100. I then had to edit my previous formula and remove the "*100" on each cell to achieve the desired result. 

## Results

- By reviewing the "Theater Outcomes Based on Launch Date" graph, we can see the most successful theater campaigns are launched in May and June, with successful outcomes decreasing as the year continues. We can also state that theater kickstarter campaigns are very successful, with a greater number of successful campaigns compared to failed campaigns for every month throughout the year. 

- By reviewing the "Outcomes Based on Goal" graph, we can see that the most successful play campaigns had projected goals of less than $5000 and between $35000-$45000. Play kickstarter campaigns are more likely to fail when the projected goals are between $25000-$35000 and greater than $45000. None of the play campaigns were canceled, which means that once a campaign is started, it is very likely to make at least some money regardless of whether it matches the projected goal.  

- One limitations of this dataset is that the analysis for theater outcomes includes all of the subcategories of theater kickstarters, not just "plays". Therefore, the conclusions we are making about the "Theater Outcomes Based on Launch Date" graph could be misleading if we want to solely focus on plays. Another limitation is the goal ranges that were created for the "Outcomes Based on Goals" sheet. We can see that a significant majority of the plays we analyzed had goals that were less than $25000. As a result, we could have obtained more meaningful results if we defined and analyzed more goal ranges below this threshold.    

- Another useful table/graph we could have analyzed is by filtering play outcomes based on country of origin to assess where in the world the most successful kickstarter campaigns are held. We could also calculate the length of time each campaign was hosted and analyze if there are trends for more successful campaigns based on how long they had lasted. 
