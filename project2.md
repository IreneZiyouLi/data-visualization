# Data Visualization Crituque by Design 

## Section 1: Background (what & why this visualization):
This visualization is found at [climate.gov](https://www.climate.gov/media/14605). It is used in the article [Climate Change: Atmospheric Carbon Dioxide](https://www.climate.gov/news-features/understanding-climate/climate-change-atmospheric-carbon-dioxide) to illustrate that the carbon dioxide level had reached a level that had never beeen attained over the past 800,000 years. 
![Line graph of Global Atmospheric CO2 level over the past 8 million year](https://www.climate.gov/sites/default/files/2022-06/ClimateDashboard-atmospheric-carbon-dioxide-image-20220616-1400px_0.jpg)
I am interested in this visualization because of a news about Kylie Jenner's "climate criminal"  After Her Private Jet Was Exposed For Taking Super-Short Flights two months ago. The [Original news Article](https://www.buzzfeednews.com/article/stephaniesoteriou/kylie-jenner-climate-criminal-private-jet) is from BuzzFeed News. Quoted from the news, "private jets have been found to emit two tons of CO2 in just one hour". Therefore, I believe it's important to alarm people who co2 is increased to a incredible level and call on action to elimate carbon print in our daily lives. In this regard, the visualization need to meet two primary requirement: 1. easy to understand by layman, 2. impress the audience to really take actions. 

## Section 2: Critiques

### Overall obeservations about this data visualization:
1. Stood out to me: the first information I caught is that the line chart shows that the number fluctuated a lot within a specific range over time. Then I was attracted by the text saying "highest previous concentration". 
2. What I found worked well: the four text explanations on the graph help the audience to better understand the data as they provide the specific events explaining the level of CO2 at the specific time. 
3. What didn't work well: based on the topic of the article and its surrounding explanation, the main goal of this visualization is to show how current concentration is much higher than any historical level. However, the point of current concentration on the chart doesn't stand out, neither by color nor size. Moreover, the point is not connected to the trend line, leaving it unclear about whether 2021 is a spike or it had been a problem for years. Therefore, important information is missing from this visualization as well. 
4. What I will do differently: As I just mentioned, I would like to make the line continuous, meaning eliminating the gap between the current concentration point and other data shown in the line. That would answer the question raised above. More importantly, I would use a more eye-catching color (dark red, for example) for the current concentration 2021 average. 

### Define the audience of the visualization and evaluate the effectiveness accordingly
The audience of this graph, in my opinion, is the general populations including a wide range of demographic group with the purpose of drawing attention on climate change related to carbon dioxide emissions. More specifically, its purpose is to show how (sadly) surprising the current global CO2 level is compared to historical records. Although the chart is easily interpretable by general public (meaning there isn't much unfamiliar/unclear information provided), this visualization is not effective in terms of conveying its main idea as the "current concentration" is not the striking point (even worser, people could easily miss that point with a fast reading). 


### Comments on Stephen Few's Data Visualization Effectiveness Profile
Overall, this method helps me effectively identify the problems/area of improvement of the visualization by thinking through each of the metrics. For example, I didn't really there is a problem with missing data until I thought about the rating for completeness. If there is anything (metric) I would add to this evaluation method, I would add a metric to evaluate if the same main idea could be perceived by different demographics when they look at the visualization. I think this metric is important, especially to this visualization, because too many highlighting (eye-catching) points on a visualization could be interpreted differently based on area of interest/familiarity. For example, people who are interested in history might be attracted by "ice age" noted on the graph rather than climate change, which definitely is not the purpose of this visualization. 


## Section 3: Sketch out a better Visualization
![test](/Sketch_s3.jpg)
For the sketch of the redesign of the chart, here are several main modifications I made:
1. connect the data from historical records to the current concentration level (which is a single data point on the original data). I aimed at finding the credible data for the years in-between to make the graph be a single trend line. 
2. Delete the text boxs of "warm period (interglacial)" and "ice age(glacial)" since they are not the main purposed of this visualization (eventually it's good to know), but they are drawing overwhelming attention and distracting audience from the dramatic increase from the past to current level.
3. change the text on the graph to red to draw attention
4. Adding a trend line of the highest historical value to make obvious contrast to the current concentration figure.

## Section 4: Test the solution (feedbacks from potential audiences)

**Interviewee 1**: student (who is also taking telling stories with data) , mid 20's
Question: what caught your eye in 10 seconds?
Answer: the current level, eventhough I haven't figure out what is the graph about, I noticed that the current level is insanely high
Question: So are you also saying that the subject of the graph is not obvious enough for fast reader?
Answer: yes, kind of. Probably due to your hand-written (lol). Also probably the header/title is not informative.
Question: what do you think the main audience that is targeted by this visualization?
Answer: I guess it would be someone who is interested in climate change and has a some background on carbon dioxide concentrations.

**Interviewee 2**: no speicific background on environmental science, mid 40's
Question: Can you understand this graph in 30 seconds?
Answer: Yes, I think I get the general idea. It shows the carbon dioxide level for the past 800,000 years, as the title says.
Question: So based on this percpetion, what is your takeaway from this graph?
Answer: there is some fluatuation in the past, and right now the number is much higher than in the past. That surprised me. I know people are talking about carbon dioxide emission all the time but it's my first time knowing how significant it increased from the past, if I understand correctly.
Question: Did you find any part of this graph unclear?
Answer: Well I think the bottom where it says "years from the present" (which the interviewee means the x-axis) is hard to understand at the beginning.

#### Reflection on feedbacks:
Overall, I think the scratch of the solution can deliver the main idea to the general public (which is also the targeted audience). Based on the feedbacks, here are some areas of improvement:
1. the title of the graph is not informative enough to provide additional information
2. should be more clear and neat to make it acessible to all people as the purpose of this visualization is to impress the audience and call for actions
3. the x-axis is kind of confusion to layman
5. improve hand-writing (outside of the scope of this course)


## Section 5:
For building the redesign solution, I used Tableau. 
<div class='tableauPlaceholder' id='viz1663724742244' style='position: relative'><noscript><a href='#'><img alt='Atmospheric Carbon Dioxide is Much Higher Than the Highest Record for the Past 8 Million YearsData:NCEI ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;CarbonDioxideover800000years&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CarbonDioxideover800000years&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;CarbonDioxideover800000years&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1663724742244');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

**Efforts on this visualization**: 
1. In order to modify the visualization to be a continuous trend line (rather than a line and a stand-alone point on the original visualization), I gathered multiple data sources for the carbon dioxide level from 1959-2022. 
2. modify the color of the line (aiming to elinimate the total number of colors used on the visualization to decrease eye-travel)
3. Based on the test on the solution, the title is changing to a conclusive, informative sentences rather than simply describing what the chart is about
4. Changes on both x- and y-axis title to make it easier to understand by someone has little background on the topic.


**Identified Area of Improvement**:
1. for the x-tick, I think it would be better to add the year number of current year like 2022 to emphasize it's the current level. However, I don't think it's feasible on tableau.


