## PyBer Analysis
---

After completing initial analysis of PyBer ride data, I created a summary of all the key metrics derived in a separate dataframe. In order to accomplish this task, in the very beginning of my analysis I merged two csv files to arrive at a single dataframe. I then calculated various metrics that can help compare and contrast the data and ultimately tell the data story, such as total rides, fares, driver count, as well as averages of some of these metrics. I used `groupby()` and `copy()` methods on the dataframe to accompish this task. While looking at dataframes and statistical summaries is good, visualizations are very important to reveal trends quickly, therefore, I also created a line graph that demonstrates the trend by City Type week over week. From this graph below, we can clearly see the leading contributing position of Urban cities as well as weekly trends, such as when demand peeks at the end of February across all three categories, suggesting it's connected with an event that impacts all three locations, such as beginning of spring break or similar.

Pyber Summary Dataframe
![Pyber Summary Dataframe](https://github.com/AnnaS0272/PyBer_Analysis/blob/master/Analysis/pyber_summary_df.png)

Pyber Summary Line Chart by week
![Pyber Summary Line Chart by week](https://github.com/AnnaS0272/PyBer_Analysis/blob/master/Analysis/Pyber%20Summary%20Line%20Chart%20by%20week.png)


While I did not encounter any specific challenges durind the analysis, there can be many. As we load and examine the data, it's importnat to check for missing values or incorrect value; we can do that using, for example, `isnull()` method. In cases if such values exist we need to either remove them from a dataset to avoid scewed averages, or substitute them to what we believe would be a reasonable substitution to preserve the sample size. 

The average fare in suburban and rural cities is approx. $5(~15%) and $10(~30%) higher respectively than in urban, and that disparity can preclude people from turning to PyBer for ride services in those areas. Based on the data, we may need to consider **adding drivers** in both suburban and rural cities to stimulate competiton, which in turn will stimulate demand and growth. It would make sense to also review the data not just by week but by **hours of the day** to better understand how demand pattern looks throughout the day for various city types. That could help create a more targeted approach. Finally, an **analysis of competitive data** or alternatives can be very useful to better plan for effective marketing and business strategy. If customers are not using PyBer, they must be using either other methods of transporttaion or PyBer's competition. Understanding the risks and propositions that may be coming from alternatives and/or disruptive technologies can only strengthen our strategic approach.  

