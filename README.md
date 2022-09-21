# mithrakumar_portfolio
This is my public portfolio for Telling Stories with Data!
https://mithraanandkumar.github.io/mithrakumar_portfolio/

# About me
Hi! I am Mithra Anandkumar. I am a rising second year Masters student in Healthcare Analytics and I love analysing data!

# What I hope to learn
I hope to learn how to effectively make charts through this course and implement it in the real world.

# Portfolio
Here's my awesome portfolio. Hope you like it!

# Assignments:

1. Visualising government debts
2. [Assignment 3&4: Critique by Design ](/assignment3.md)
3.
4.






# Visualizing Government Debts

Data Source:
The data for this assignment was obtained from the Organization for Economic Co-operation and Development (OECD). The general government debt-to-GDP ratio serves as an indicator of the government finanace's sustainability. 

Visualization: 

The visualization consists of a bar graph which shows the distribution of debt-to-GDP ratio across various countries for a selected year ( I chose to view 2019 data). Countries Germany,Australia, United Kingdom, Canada, USA, and Japan are higlighted with bright colours along with the OECD average. The OECD avearge is colored black to serve as a comparison with the selected countires. The color palette is set to a default palette by the OECD website. 

From the graph, it can be inferred that the debt-to-GDP ratio for Germany and Australia are below average whereas the debt-to-GDP ratio for UK, Canada, USA and Japan are above the avearge. 

<iframe src="https://data.oecd.org/chart/6OfF" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true">OECD Chart: General government debt, Total, % of GDP, Annual, 2021</iframe>


i. Visualisation Using Flourish

Visulaising the same data using Flourish. Flourish is an online data visualisation platform used to make powerful charts. Using Flourish, I plotted a line graph (grid of charts) that shows the trend of debt-to-GDP ratio for each country across the years 1995 - 2019. The X-axis represents the years and the Y-axis represents the dept-to-GDP ratio. The colour Dark Red (#730202) was utilized throughout to eschew needless ornamentation. The title of the chart is simple and short - General Government Debt 1995 - 2019 -> which allows the user to understand what the chart represents in an easy manner. I added a footer to include the source of the data and a URL was embedded into the chart. This would help the user to view the data source in an easy manner. I changed the configuration in Flourish to make the graph look more like sparklines. 

The scaling of the y axis is a linear scale with increments of debt-to-GDP ratio. I decided to not include an explicit y-axis title (and ticks) to create a cleaner look. Each data entry is still spaced evenly on the vertical axis. The x-axis maps the year and is also a linear scaling. I opted to remove the actual x-axis and keep the increment values to have a cleaner more continuous look.  

<div class="flourish-embed flourish-chart" data-src="visualisation/11155528"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

ii. Bar Chart Race using Flourish

For a new visualization, I decided to use Bar Chart Race which is different from the traditional bar chart. What I wanted to show with this visualization is more than just the fact that the countries are in a large amount of debt but to put those numbers into perspective with data aacross different years. I wanted to show the viewrs that debt-to-GDP ratio has been changing over the years due to many unstated factors. I wanted to build curiosity in the viewer to search more for the unstated factors. 

I used a bar chart race as the data moved from 1995 to 2019. This gives a sliding scale that can be used to create races. I did some pre-processing and cleaning to rearrange (take a transpose) the data. I used flags so that the viewer can easily associate to the country. The race is in a loop starting from1995 to 2019. There is a 30 seconds break before the next loop starts playing. If the user wants to view the graph for only one particular year they can do so by dragging the slider on the selection bar to the year. The bar chart above will be updated to the dept-to-GDP ratio in the selected year. 

I wanted to use subtle colours and a sequential palette for this graph but Flourish gave me only a few options to play around with. I finally ended up using the antique palette from Flourish. Since the colors saturations are subtle, it won't be too bright on the viewer. I added a simple title - "Debt Crisis?" and added footer to include the source of the data. 
 
<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/11162358"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


