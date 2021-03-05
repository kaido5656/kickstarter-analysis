# An analysis of Kickstarter campaigns
perfoming analysis on kickstarter data to uncover trends and potential insights for launching a successful kickstarter
##Overview and analysis purpose
  For the purpose of this analysis 4109 different types of kickstarters will be used with the subsequent data. The types of data that will be used with vary from date launched, date finished, number of backers, goal amount, pledged amount, country of origin, and whether or not the campaign was successful. The aforementioned types of data will being used in Excel to further extrapoate and return new information.

## Analysis and Challenges

  In assisting Louise with her endeavors to launch a successful kickstarter, I was tasked with looking further into the relationship between the outcomes with goals, and launchdate in mind. First in determining the relationship between outcomes and the launchdate for each theater campaign a pivot table was used in focusing the results. With the properties being: rows as the date created conversion, columns as the outcomes, values as the count of outcomes, and filter by type of category and year started.

![theater_vs_outcomes](theater_vs_outcomes.png)

### Analysis Cont.

Lastly I determined the relationship between outcomes based on goals. For this data I created a new worksheet with different goal markers, number of outcomes based on campaign success(barring the still live campaigns), and percentage of success relative to the amount of total campaigns in each goal grouping. Luckily I experienced little to no issue with my analysis, however the mildy repetative nature of the formulas used in finding outcomes was mostly circumvented by making each data point static and copying it over to a different outcome and simply editing the eoutcome to match.

![Outcomes_Vs_Goals](Outcomes_Vs_goals.png)

## Results

  A few conclusions thats can be drawn from the Theater outcomes vs launchadate data are that the most active and successful month to launch a theater based kickstarter would be May. Another conclusion is that by manpulating the pivot table to show specific years, show that the most active years were 2014, and 2015 with the later years begin to taper off in activity. Upon looking at the outcomes vs goals data one may conclude that goals that are below 15000 USD have more than 50% rate of succeeding with the chance of success gettng higher the lower the goal is from 15000 USD. A few limitations of this dataset are that does not provide any information upon how long each of the kickstarter campaigns ran for, which would help provide helpful information pertinant to Louise as she nears the end of her campaign. A possible graph that could be made to gather more information on would be one inlcuding goal, outcome, and date ended conversion to see how these kickstarters faired against others and if the successful campaigns had longer campaigns or shorter ones.
