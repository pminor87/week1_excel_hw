# Kickstarting with Excel

## Overview of Project
Analyzing Kickstarter Dataset to draw conclusions using trends based off certain conditions.

### Purpose
Purpose is to utilize data science in order to answer questions provided by the client.

## Analysis and Challenges
Analyze datasets on Outcomes Based on Launch Date and Goals.

### Analysis of Outcomes Based on Launch Date
Launch Dates executed in May and June seem to have the highest historic success rate.
![Outcomes Based on Launch Date](https://github.com/pminor87/week1_excel_hw/blob/main/01-Kickstarter/Submission/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
There are two conclusions to draw from the dataset. Goals of less than $5k and between $40k and $45k tend to have the highest success rate, however there is a much smaller sample size for the latter. The confidence level in success rate between $40k and $45k goals is much lower than that of goals set less than $5k.
![Outcomes Based on Goals](https://github.com/pminor87/week1_excel_hw/blob/main/01-Kickstarter/Submission/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
I had a small challenge with the countifs function when attempting to capture data between goal ammounts. I was attempting to nest the "AND" function within the countifs function but realized it was not neccessary because the countifs function already utilizes multiple criteria.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclusion is that May and June tend to have the highest historic success rate for campaigns started in those months.
The second conclusion is that those same months also have very high failures which means that the highest number of kickstarter campaigns were also started in that month which may create more competition for potential backers.

- What can you conclude about the Outcomes based on Goals?
Since there is a lower confidence in the success rate data for goals between $40k and $45k I would not suggest using those data points as viable conclusions.
Instead I would conclude that there is a negative relationship between the amount goal amount and the success rate, with a steep drop off when goals exceed $5k.

- What are some limitations of this dataset?
When projecting successful campaigns based on launch date, success rate should be measured rather than total successes. The data can be misleading if you use total successes because there may have been a larger amount of campaigns also started in those months with the highest number of successes.
I reccommend utilizing more statistical methods when projecting success and success rate based off certain criteria to also give a confidence level for each subset of data.

- What are some other possible tables and/or graphs that we could create?
When analyzing Theater outcomes based on launch date, I would include a success rate calculation and then use that data to project success rate by month to give the client a better reccommendation on when to launch their campaign.
A bar graph would probably also suffice to portray the data tables.
