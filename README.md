# kickstarter-analysis
Analysis on Kickstarter data module 1

# Kickstarting with Excel

## Overview of Project

For our first weekly challenge we are to analyze the kickstarter data that Louise provided us with in order to exorcize the new excel skills we have learned. We will have to create two new analyses: outcomes based on goals and outcomes based on launch date.  

### Purpose

The purpose of this project was to help Louise compare the different outcomes between campaigns in relation to their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

By creating a pivot chart using the campaign data I was able to combine and filter the results for parent category "theater" to determine the total amount of successful, failed, and canceled theater project outcomes there were by month. I then created a pivot chart which can be found here: ![Theater_Outcomes_vs_Launch](/Users/alexislarson/Desktop/resources/Theater_Outcomes_vs_Launch.png) 

### Analysis of Outcomes Based on Goals

By creating various goal ranges and using the countifs function I was able to group the number of successful, failed, and canceled projects of plays there were in the theater based on the targeted goal amount. I then created a line chart to visually see the results between the goal ranges and the percentage of the play project outcome. The percentage amount was determined by dividing the number of outcomes by total project outcomes within a goal range period. You can find the line chart image through this path:  ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/88064931/147999102-1b18f06e-76ab-4ae2-bc2b-5fd2f9edf354.png)


### Challenges and Difficulties Encountered

I personally did not have any issues manipulating this data, using the formulas needed, or creating charts or pivot tables therefore, I did not encounter any challenges, however, I can see how this deliverable could have been challenging for someone who did not complete the mini assignments within module 1. I can agree that deliverable 2 was the most time consuming in terms of having to manually type out the goal ranges as well as having to update the "outcome status" within the formula for each section. Also, I initially was attempting to create a line chart by creating a pivot table first which was not giving me my desired results, but I rectified that issue by just creating the chart with the data from the table and removing the fields I did not need in the chart. I will say that I did find it challenging pulling my image path details, but a quick google search helped me figure it out.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. May appears to be the best time frame to launch a project and obtain funds to meet the project goal and get a successful outcome. 
2. Although, October didn't have any canceled projects it still had a pretty high failure rate considering the huge drop the month before and the north after. It was actually the highest of the year hence I do not believe projects should be launched in October. 

- What can you conclude about the Outcomes based on Goals?

1. Projects with a goal greater than 40,000 have a higher chance of failing and meeting their pledge goal. 
2. The best chance for a successful outcome would be to keep the goal amounts under 4,999. 

- What are some limitations of this dataset?

1. The country should have been analyzed as well. Doing so would allow you to identify which country you should focus your efforts in to ensure resources and funds are not being underutilized and wasted. 

- What are some other possible tables and/or graphs that we could create?

1. I think we should have created a graph using the method for deliverable 2, but instead of using goal ranges we analyze all of the subcategories. Example can be seen here: ![subcategory_vs_Outcomes_extragraph](/Users/alexislarson/Desktop/resources/subcategory_vs_Outcomes_extragraph.png)
