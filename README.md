# Kickstarting with Excel

## Overview of Project

### Purpose 
  The purpose of this assignment was to visualize campaign outcomes based on launch date and to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount in order to provide real world data analysis to customer Lousie regarding her play *Fever*'s potential future campaigns. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
  An analysis was performed looking at outcomes based on launch date. Through this analysis it was determined that the most successful campaigns were started in May with the least number of successful campaigns starting in December.  Additionally, the least amount of failed campaigns occured in the month of November and the most failed campaigns started in the months of May and October, respectively. Infact, very few campaings were canceled in general. Finally, it is important to note that zero campaigns were canceled in the month of October. See below *Figure 1*.

*Figure 1*
![Theater_Outcomes_vs_Launch](https://github.com/maureengamache/Module-1-Challenge/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
  An analysis was performed looking at outcomes based on funding goals. Through this analysis it was determined that the percentage of successful campaigns is higher than the percentage of failed campaigns, between less than $1,000 and $15,000; and then again between $35,000 and $45,000. It is important to note that all campaings with a goal over $45,000  and less than $49,999 failed and that less than 20% of campaigns with a goal of $50,000 or more were successful. Additioanlly, the highest percentage of successful campaigns had goals of less than $1,000.  See below *Figure 2*.

*Figure 2*
![Outcomes_vs_Goals](https://github.com/maureengamache/Module-1-Challenge/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
  During this analysis several challenges were encountered. The first was ensuring that all pre-work was correctly completed, particularly the text to columns for the Parent and Subcategory categories of theater/play. Without correctly separating these two text, additional data was pulled into my pivot tables and graphs for other parent/subcategories of theater/spaces and theater/musical. The second challenge encountered was using the multiple criteria and range formula of COUNTIFS, with an "s", instead of the singular criteria and range COUNTIF. Additional challeneges could have been manually retyping all of the COUNTIF formulas for each of the 12 rows and 3 columns in the Outcomes Based on Goals chart, without making an error. Therefore it was extremely useful to be able to search, find, and replace the names of "successful", "failed" and "canceled" in all of the COUNTIFS formulas.   

## Results
  The are several conclusions that can be drawn from the data analysis of Outcomes Based on Launch Date and Outcomes Based on Goals. These analyses provided valuable insight, however, there are limitations to the data provided. In order to address the limitations of the data set used for this analysis, recommendations will be made and further analysis completed to provide a more complete picture of the functional and temporal market in which Lousie should launch her next campaign for the play *Fever*. 
  The conclusions that can be drawn from the Outcomes based on Launch Date are that, in all countries, the most successful campaigns for theater/plays is May. An additional conclusion is that the worst month to begin a campaign, in all countries, for theater/plays is December. Therefore, based on this data, Lousies should launch her next campaign in May. 
  The conclusion that can be drawn from the Outcomes based on Goals, is that the most theater/plays are successful in achieving their goal if the goal is less than $1,000. It is important to note that plays with larger than $1,000 goal amounts can be successful, but the percentage of plays that are successful begins declining after a $1,000 goal price point.
  There are several limitations of the data set, particularly the country in which Louise would like to release her play may not have May as the most successful month, as the data included all countries. Additional limitations are that the goals of each campaign are subjective numbers determined by people with unknown credentials. It is possible that analyzing percent funded may be a more compelling measure to analyze, as it would help Louise to determine which plays would have out of pocket expenses to produce. Given these limitations a better analysis graph might be Outcomes by Percent Funded in Country of Release. 
