Introduction
This page implements detailed design of Q3,
displaying the relationship among COVID-19 daily deaths, population density and GDP worldwide.

Pre-processing
The data of daily death rate (of 11/3/2021) due to COVID-19 is from Johns Hopkins University and the population density,
GDP data (of 2017) are from World Bank. I use the "CountryCode" to combine the dataset, and export them as a .csv table.
In the table, "value" represents the continent of country,
which is used to classify countries in different colours in my visualization chart.

Interaction
1)Move the mouse over one circular area,
and a black label will appear next to the mouse, showing the name of country and the data of population density.
Also with two red auxiliary lines and marks, which give the accurate coordinate value.
2)Move the mouse over one circular area,
all countries on the same continent will be highlighted in the same color,
and countries on other continents will be grayed out.
3)Use the mouse to select an area, the brush will enlarge the area and x-axis to show partial chart clearly.

Note:
If the label is not displayed, please wait a few seconds or move the mouse from another direction.













Note:
If the label is not displayed successfully, please move the mouse from another angle and try again.