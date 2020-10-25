# Kickstarting with Excel

## Overview of Project

### Purpose
To do an analyses of outcomes based on goals and outcomes based on launch date for Louise. 
To do an analyses of how different campaigns fared in relation to their launch dates and their funding goals.
This was done so that Louise would be able to know the following; time of year to launch kickstarter campaign, type of campaign, type of play to launch.  All of this was to provide the statistical data for her to launch her kickstrter campaign for "_Fever_".

## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date
Created a new column "_Years_" based on data from another column. Created and filtered the Pivot Table (Outcomes by Launch Date), to show the requested ranges. Created a chart from the Pivot Table. Labelled and saved chart as a PNG.
<img src="Resources\Theater Outcomes Based on Launch Date.png">

### Analysis of Outcomes Based on Goals
Created a new worksheet for Outcomes based on Goals. To do this I used the **=countifs()**function and learned that each had different criteria to input. also used the **=Sum()** function. Also used the percentages function.  Created a line chart while filtering out information to achieve the correct ranges on the _x-axis_ and _y-axis_. Labelled and saved line chart as a PNG.
<img src="Resources\Outcomes based on Goal.png">


### Challenges and Difficulties Encountered
I encountered difficulties at first with the **=countifs()** especially when the criteria changed to between specific amounts i.e. 1000 to 4999, etc. Also had a minor difficulty in doing the line chart but finally figured out what went on the _x-axis_ and _y-axis_.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
May -August has the highest success rate for a kickstarter, whereas the last 3 months of a the year October - December have the lowest success rate for a kickstarter.

- What can you conclude about the Outcomes based on Goals?
Most successful kickstarter range ammounts are between 1000-4999 and 35000-44999. Anything under 20000 has a 50% chance of success.
Most failed kickstarter range amounts are between 20000-34999: anything over 45000 has a higher chance of failure.

- What are some limitations of this dataset?
The relationships between the Play and Theater campaigns, used a representative sample of the population.
The duration between the launch dates and end dates are inconsisitent, which could influence the outcomes of the amount of money raised.
The range between the dollar amounts could be shortened to smaller increments to get a better idea as to which was more successful.

- What are some other possible tables and/or graphs that we could create?
In Line charts you could have also used a line with marks to better see the corelation.Clustured column, Clustered Bar chart, and stacked bar chart would be better visually to do a comparison of the statistics at a glance.
