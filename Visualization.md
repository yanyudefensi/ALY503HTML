# Family3 and Family2 Electricity Visualization

## Family3 Part

### Consideration and Final Visual Target:

I would like to know the electrical appliance usage for each day in Home 4, especially the percentage of electrical load. However, considering the long timeline in the dataset, using one graph to show the 24h electrical load share of household appliances for each day of household 4 would result in too long x states reducing readability. Therefore, I replace the x-axis timeline with the month, and the final visualization goal is the average value of the 24h electricity load share of household 4's household appliances for each month.

### A Rationale for Design Decisions:

My visualization goal needs to include two dimensions: TimeLine and the percentage of electrical load of each household appliance, the candidate diagrams are pie chart, bar chart and stacked bar chart, the pie chart cannot show the trend of electrical load over time, and the bar chart cannot show the percentage of electrical load, the stacked bar chart meets the visualization conditions of both dimensions and is the best choice.

<iframe src="https://yanyudefensi.github.io/ALY503HTML/plotly.html" width="100%" height="500">
</iframe>

### Discovery:

1.	From June to December 2016, refrigerators electricity overload rank 1 of all appliances, but by January 2013, they shrank to 1/7 of their original consumption, guessing that the low winter temperatures reduced refrigerator usage.
2.	Kitchen appliances are found to be in use from 6am-8am and 6pm-7pm
3.	Microwave were found to be in use from 11am-12am and 6pm
4.	Because of the relationship between the direct sun point movement, the closer the time is to winter, the longer the time of darkness, the greater the proportion of time and load of light use

## Family2 Part

### Consideration and Final Visual Target:

I want to understand the daily electrical load and trends of the appliances in my home5 and capture important anomalies, such as power limit days, blackout days, or whether the electricity use of rank3 appliances has changed over time.

### A Rationale for Design Decisions:

Candidate images to show time trends are bar charts, scatter charts, and linear charts, which are not suitable because of the long-time span of the time series displayed and the daily granularity of analysis. Because up to 8 types of furniture are displayed, a scatter plot would reduce readability, so it was finally decided to use a line chart with an additional measurement scale to help the reader see the specific value of the electrical load of the furniture on a given day.

<iframe src="https://yanyudefensi.github.io/ALY503HTML/altair.html" width="100%" height="500">
</iframe>

### Discovery:

1.	Between 2012-9-14 and 2012-9-15, between 2012-9-27 and 2012-9-28, the power load of each furniture drops significantly, so there may be power restrictions on this day.
2.	Between 2012-9-8 and 2012-9-28, the electrical load of the microwave oven was 0, but the electrical load of other furniture existed, so the microwave oven was damaged during this time.
3.	The power load of the refrigerator has been rank1, but the trend of the power load has changed. Before September 2012, the power load of the refrigerator fluctuated around 4,500,000, but after that time period the power load of the refrigerator fluctuated around 3,500,000.











