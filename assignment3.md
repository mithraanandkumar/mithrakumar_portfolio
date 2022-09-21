# Assignment 3&4: Critique by Design

## Introduction

I decided to critique and redesign the visualization called "The World's 25 Largest Banks by Market Capitalization" which can be found in the following link: https://www.swissinfo.ch/eng/business/by-the-numbers_is-switzerland-really-the-country-of-bankers-/40473658

Context:

The article talks about Switzerland's banking indusctry and its working labour force in the financial sector. The paragraph supporting the visaluization talks about how Switzerland's individual banks are no heavyweights in terms of market capitalization in comparison with other countries. 

Why did I choose this visualization?
I chose this visualization bacause at first glance I could not comprehend what the visualization was communicating. I wanted to try and improve the visualization and help other people like me who struggled to understand the graph. 

Views on the Visualization:

It’s a strange design choice. The only thing that worked for me is the labelling, as it is easy to associate the bank with the bar. There are a lot of things that didn’t work for me. 

1. The arrangement is that of a pie chart but the areas are misleading because it's actually a circular bar chart. The use of a pie slice massively distorts/exaggerates the data. 
2. The circular grid line fades away making it difficult to interpret the data for the lower-left bars. 
3. The color coding doesn’t work for me. It is hard to differentiate the color for UK and Switzerland. 

I would choose a better visualization to represent the data either that of a treemap or a horizontal bar chart.

The primary audience for this tool are aspiring bank professionals and economists. The visualization is not effective for reaching that audience. This is because the graph is too fancy for a simple data. It is hard to interpret when the grid lines fade away. It doesn't make sense to use a spiral bar chart when a linear display facilitates more accurate comparisons of the bars. 

The “Data Visualization Effectiveness Profile” method was very helpful in evaluating the data visualization selected. I was able to identify my views on the visualization and formulate few ideas to change the visaluzation. I went through the article to understand the context behind the graph. The graph fails to support the paragraph in terms of highlighting the country the whole article was focused on. I would get rid of the spiral chart and probably use Treemap or Horizontal bar graph to represent the data. I would change the color palette to highlight Switzerland. I would also change the title to support the article. 

Wireframes:

I created two wireframes for my visualization. I created a horizontal bar chart and a treemap. 

![The World's 25 Largest Banks by Market Capitalization](https://user-images.githubusercontent.com/113000842/191404378-6b0c0556-8422-486e-af5b-3e2c59e879b5.png)

My thought processs to create this wireframe was to get rid of the spiral chart and create a simple chart to portray the data accurately.

<img width="635" alt="Bank Based Market Capitalization By Country" src="https://user-images.githubusercontent.com/113000842/191404418-ac44365c-89eb-4a8f-840e-6dceb2ef6f54.png">

My thought processs to create this wireframe was to show a contarst between Swizerland and the other countries by creating a treemap with sequntial palette to indicate a contrast. 
 
### Testing the solution
I got feedback from 2 people on my wireframes, each of which made me realize different things that I could improve with my visual. 

Viewer 1 (in their 20s):
Viewer 1 felt that the treemap shows what the market capitalization is contributed by banks across different countries, and that the treemap communicates this at a country level thus allowing viewers to understand at a broader level. 
Viewr 1 was not receptive to seeing so many different bars from the first wireframe and suggested to limit it to 10. They also pointed out that brazil and switzerland seem to be of the same size, however were represented by different colors which was misleading.
Overall, viewer 1 felt that the sequential color palette looked good on the treemap but suggested to highlight the country in focus. From first look, they felt it looked like the insight is that US is performing really well on banking based market capitalization. 

Viewer 2 (in their 50s):
Viewer 2 felt that the horizontal bar graph was clear and communicated the size of the bank in terms of market capitalisation. They also felt that the treemap had colour gradation, but the volume of market capitalisation was not mentioned. They suggested to add it below the country name. They also felt a little lost in terms of what was being communicated from both the graphs.  
 
Based on the feedback provided by the 2 users, I moved on to change my visual accordingly.

Building my solution:

I decided to stick with the treemap as this chart communicates what the article focuses on - Switzerland's individual banks are no heavyweights in terms of market capitalization in comparison with other countries.

Treemap allows you to represent a hierarchically-ordered (tree-structured) set of data. The conceptual idea is to compare market capitalization quantities and show patterns within countries. For that purpose, I used rectangles of different sizes and colors to display the dataset from a different perspective. The goal of this visualization is not to indicate the exact market capitalization values, but to “break” the dataset into countries and quickly identify Switzerland's market capitalization. For this purpose, I used two contrasting colors to highlight the country in focus Switzerland. I chose a title that adds value to the visualization. 

I found this critique method very intuitve and it was easy to focus on what needs to be imporved and more importantly, it was very helpful in comparing the redesigned vizualisation with the original in the same categories to see if there are improvements.

Here's my visualization:

<div class="flourish-embed flourish-hierarchy" data-src="visualisation/11239665"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

