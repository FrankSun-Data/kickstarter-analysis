## Overview of the Project:
### The purpose of this project is to determine the relationship between the launch dates and funding goals of different campaigns by visualizing the campaign outcomes using the Kickstarter dataset.
## Analysis and Challenges:
### In order to see how theater outcomes are affected by the launch date, the whole Kickstarter dataset are selected to create a pivot table. Parent category and years are put into the filters, years for the rows, and the outcomes for the columns and values. YEAR function is used to return the year corresponding to a date. By selecting “theater” in the parent category section, the table now shows the outcomes corresponds to each month. And a line chart can be made to visualize the trend.
### The COUNTIFS function is used count the number of times when all applied criteria are met. Number of successful, failed and canceled can be counted by using the COUNTIFS function. And the percentage of each category can be calculated by dividing the number over the total projects. Another line chart can be made to show the outcomes based on goal.
### When writing the COUNTIFS function at the beginning, I copy the function into other cells to save time. But it shows invalid number. Then I realize that I forget to freeze the selected column by using “$”. The problem is solved after I freeze the column.
## Results:
### Based on the “Theater Outcomes by Launch Date” line chart, the number of successful and failed present a similar trend throughout the year, with a climb up from March to May, and a descending trend from May to December. A small come back happens to both outcomes between September and October. While the outcome for canceled projects has a relatively stable trend. We can conclude that the launch date has a similar affect to both successful and failed outcomes, since they show a similar trend. And the launch date has relatively no effect on the canceled outcome.
### Based on the “Outcomes Based on Goal” line chart, the trend of percentage successful and failed is symmetrical. The percentage successful decrease with the increasing of goals. The number rebound at 25000 and drop again when reaching 44999. The percentage failed shows a opposite trend compared with the percentage successful. The percentage canceled is 0% for all range of goals, thus its line trend stays on the x-axis. We can conclude that the goal has a effect on both successful and failed outcomes, in a opposite way, and has no effect on the canceled outcome. (For the “Plays” subcategory only)
### There are some limitations of the dataset. The percentage canceled show 0% for all range of goals. However, it is only for “plays”. More subcategories should be counted and form charts to compare the relation. And more charts should be made for “outcomes by launch date”, by changing the parent category. By comparing more tables and graphs, we might have a different conclusion.
