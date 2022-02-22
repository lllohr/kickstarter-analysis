# kickstarter-analysis
Performing an analysis on Kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project
The project used Excel to explore the data in the Kickstarter Challenge. The data analysis illustrates the following data points: outcomes based on goals and outcomes based on launch date.

### Purpose
The purpose of the project was to demonstrate and exercise new Excel skills learned in the first module of the class. The project required skills such as Box and Whisker graph, how to insert and manipulate a pivot table, utilization of formulas in Excel such as countif and sum, creating and saving .png images, and how to display data in a simplistic manner that can be shared with stakeholders and parsed.

Further, the stated purpose of the project was to help Louise, who had recently completed a fundraiser for her play Fever. Her play had come close to meeting the fundraising goal. Our purpose was to help Louise determine how different campaigns fared in relation to their launch dates and their funding goals.
 
## Analysis and Challenges
To complete the analysis, I followed the steps given succinctly and precisely. If I did not understand what was being asked, I read through the instructions again. The assignment required some knowledge of how to insert a pivot table from the main sheet. To perform this task, I clicked on the “insert” and found the “pivot table” icon, selected the data from the entire sheet, and inserted the pivot table into a new sheet. 

From the new sheet, I labeled it and performed the various analyses to visualize the data in a more understandable format. Using the pivot table filters, I could create rows and columns which functioned to display the data in multiple ways. 

The next step was to create a line graph and manipulate the data. This was straightforward, although the customization took some trial and error. After creating the line graph, I was able to visualize trends, separate successes from failures and parse the data in a digestible way. 

### Analysis of Outcomes Based on Launch Date
The first task was to analyze outcomes based on launch dates. This required using a pivot table and a line graph to visualize the results of this analysis. For this, I created the following line graph:

![Theater Outcomes Based on Launch Date]( https://github.com/lllohr/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

In this line graph, I can see that June was a successful launch month. What can I parse from this data? It appears that in both successful and failed campaigns, June did well. In December, the outcomes were very low. October was also a month that saw a spike in outcomes.
 
### Analysis of Outcomes Based on Goals
To analyze the outcomes based on goals, I created a new sheet and labeled columns according to criteria specified in the directions: 
•	Goal
•	Number Successful
•	Number Failed
•	Number Canceled
•	Total Projects
•	Percentage Successful
•	Percentage Failed
•	Percentage Canceled

The instructions stated that I should filter each column in the Kickstarter sheet in order to populate the fields in the new sheet. This is where I ran into issues. My data was not displaying correctly, the countif function was returning errors. It took multiple tries, much research, and help from the help desk to find the way to use the countif function correctly. However, I did not have the same difficulty when asked to use the sum function to populate the data. I was able to populate the fields as follows:
![Countif Chart]( https://github.com/lllohr/kickstarter-analysis/blob/main/countif_data.png)
 

I was able to create this graph showing the outcomes based on goals: 
![Outcomes Based on Goals]( https://github.com/lllohr/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

What the data showed me was that the failure rate increased significantly at the goal of 30,000 to 34,999 range. The goals were met at a higher rate, whether the campaigns were successful or not, when the goal was 5000 or less. The data told me that goals were met when the expectations were lower. 

### Challenges and Difficulties Encountered

My biggest challenge was using the countif formula. I received errors, no matter how I tried to order the command. What worked in the end, was to go into the main sheet, select the specific row/column manually. When I attempted to use the filters, the data was not displaying correctly. I did reach out to the help desk twice, found useful websites, and watched videos. For example, this explanation of countif on W3schools: [W3schools]( https://www.w3schools.com/excel/excel_countif.php/). This provided a robust explanation that helped me understand the purpose of the function. Where I struggled the most, was understanding where to put the comma, semicolon, etc. Additionally, I watched this video to illustrate how to use countif appropriately: [MS Excel - COUNTIFS with Multiple Criteria]( https://youtu.be/azx7Nh8QXzY/). 

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
It appears that in both successful and failed campaigns, June did well. In December, the outcomes were very low. October was also a month that saw a spike in outcomes. 

- What can you conclude about the Outcomes based on Goals?
What the data showed me was that the failure rate increased significantly at the goal of 30,000 to 34,999 range. The goals were met at a higher rate, whether the campaigns were successful or not, when the goal was 5000 or less. The data told me that goals were met when the expectations were lower. 

- What are some limitations of this dataset?
One of the limitations of this dataset is that there is so much data to look at and there are some questions that aren’t answered. Why did these campaigns fail? Do we have any survey information on why they were canceled? What do we know about the high fundraising? Are they outliers? Should they be trusted? 

- What are some other possible tables and/or graphs that we could create?
We could compare the different categories and see which ones raised the most. Did documentaries raise more money than plays? Could we compare the fundraising across categories and find out what made them successful? 

