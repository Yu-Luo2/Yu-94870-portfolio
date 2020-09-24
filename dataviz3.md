# Step one: find a data visualization
<iframe src="https://ourworldindata.org/coronavirus-data-explorer?zoomToSelection=true&country=&region=World&casesMetric=true&interval=total&aligned=true&hideControls=true&smoothing=0&pickerMetric=location&pickerSort=asc" loading="lazy" style="width: 100%; height: 600px; border: 0px none;"></iframe>

# Step three: wireframe a solution
![Explanation of data viz](2.png)

# Step four: Test the solution
## Friend 1
Q1: I feel confused about total cases, exsiting cases and cumulative cases trend. I can't understand the definition of them. I guess that the cumulative cases trend is the predicted value by prior actual cases number.

Q2: The gragh describe to me that for the fivecountries referred, after a time point,thecumulative cases trend exceeded actual cases number,thus number of confirmed cases is lower than the actual. and I can't realize toal cases and existing cases,because i think toal cases must be higher than the existing ,because it's total.

Q3: Why actual cases number decreased too much fast than the trend. what the definition of total cases and existing cases.

Q4: People, scholars, government officer

Q5: Denote which line is cumulative trend, whichline is cases number, and add detailed definition of data name.


## Friend 2
Q1: The current growth trend of COVID-19 cases in various countries and the comparison of detected and actual cases.

Q2: The cumulative increase in cases and the number of cases in each country are consistent.

Q3: Why are the total cases in some countries higher than the actual cases?

Q4: Donald Trump

Q5: No.

# Step five: Build your solution
<script type='text/javascript' src='https://prod-useast-a.online.tableau.com/javascripts/api/viz_v1.js'></script><div class='tableauPlaceholder' style='width: 1536px; height: 677px;'><object class='tableauViz' width='1536' height='677' style='display:none;'><param name='host_url' value='https%3A%2F%2Fprod-useast-a.online.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='&#47;t&#47;yus' /><param name='name' value='Assignment341_0&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='showAppBanner' value='false' /></object></div>
<div class="flourish-embed flourish-chart" data-src="visualisation/3825334" data-url="https://flo.uri.sh/visualisation/3825334/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# Written summary
I includede two visualizations, beacause I think these two together can so that people can find the informaiton of each country more quickly.
Based on my friends 1's feedback - "Denote which line is cumulative trend, whichline is cases number, and add detailed definition of data name.", I decided to create a visualization with bar charts showing the total confirmed cases for each country on the left, and corresponding line charts showing the trend on the right. And I will replace the variable - "existing cases" with "cumulative deaths", because friend 1 found it confusing. However, I couldn't find such a visualization after trying many templates. Therefore, I splited one visualization into two. The bar chart can give audience a very straightforward perception that which countries have the most number of COVID-19 confirmed cases. I also use different colors to differentiate countries belonging to different continents. All these measures aim to increase the instant accessibility of information needed. And the grid of line charts give each country a seperate graph showing its trend and other important information such as "new cases", "new deaths", "cumulative cases" and "specific date" in the popups. With these two visualizations, people can find the detailed and complete information as quick as possible.

