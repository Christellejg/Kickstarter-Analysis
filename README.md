# Kickstarting with Excel

## Louise’s play Fever came close to its fundraising goal. Louise wants to know how different campaigns did in relation to their launch dates and their funding goals. This analysis was done to visualize the campaign outcomes based on their launch dates and their funding goals.

### The purpose of this analysis is to see the relationship with campaigns launch date and their outcomes based on their goals. 

## For the Theater Outcomes by Launch Date, I created a pivot table and line graph visualize the campaign outcomes: successful, failed, and canceled based on launch date. For the Outcomes Based on Goals, I use the COUNTIFS() functions to populate the number successful, failed, and  Canceled project, along with their percentage. I also created a line graph to visualize the campaign outcomes.

### In the “Outcomes Based on Launch Date” sheet, using the pivot table help me understand around what months of the year was more successful to launch a theater project. The analysis of the table showed that project that launched in the months of May and June had the most success.

### In the “Outcomes Based on Goals” sheet, I did an analysis on the numbers of successful, filed, and canceled plays within different goal dollar-amount ranges. We also did an analysis on the percentage of successful, failed, and canceled projects.  The outcomes showed that the percentage that had the most success on their fun-raising goals for plays were those who had a goal of $4,999 and less. As for the percentage of the failed goals, were those who had large project goals, that were not met. We also can see that there were no plays that was canceled. That entire column was 0.

### Challenge that I encounter was in the Numbers of Failed column while working on Deliverable 2. In this column, Column C, I did the same thing I did in Column B where I was using the COUNTIFS()function to populate the "Number Failed", using the proper filtering corresponding ranges. At the end, I used the SUM() function to add the entire column, which is to match the COUNTIFS() greater than zero function, along with the proper filtering. However, the sum of my Column C did not match my COUNTIFS total. It was off by 4 counts, although, I use the COUNTIFS() function correctly for each cell in that row.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 
	1. The month of May and June are the best months to launch a project. These were the two months with the largest success rate based on launch date.
	2. The month of December is probably the worse months to try to launch a project. There may be many factors that can contribute to that. The end of the year is when people are spending more money on different things such as Christmas, gifts, end of the year activities, flights to visit family/friends, etc. So, to plan a launch date in that busy month could leave you with little success of launching your project in the hoped to raise funds.

- What can you conclude about the Outcomes based on Goals? What we can conclude about the Outcomes based on Goals is that there is more success when the goal isn’t high.

- What are some limitations of this dataset? The limitation of the dataset is the missing values in the Number of Failed (Column C). 

- What are some other possible tables and/or graphs that we could create? We can also create a pie graph to help us have a better visualization of the percentages of successful, failed, and canceled projects.
