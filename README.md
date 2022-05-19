# Kickstarting with Excel

## Objective



### An analysis was performed using Kickstarter data to help inform an up and coming playwright Louise about crowdfunding campaigns. The data will determine what factors may help her have a successful campaign for her play with a $10,000 budget. I will be using excel to organize, sort, and analyze crowdfunding data from different campaigns to provide Louise with essential information how different factors influence campaign outcomes.

## Analysis and Challenges
 
### Analysis of Outcomes Based on Launch Date
In Deliverable 1, to visualize the campaign outcomes (successful, failed, and canceled) against the launch date, I created a pivot table and chart using the Kickstarter data. I filtered the data by the parent category, theater. I then placed the outcomes in the columns and the launch date in the rows.


### Analysis of Outcomes Based on Goals
In Deliverable 2, I visualized the percentage of successful, failed, and canceled plays based on the funding goal amount in the form of a line chart. To perform this analysis, I started by creating a chart with goal amounts for the rows and the Number of Successful, Failed, and Cancelled campaigns as well as percentage of each of those in the columns. To find this data, I created COUNTIFS staments to pull data from the Kickstarter data tab. I then created a line chart with the goals on the x-axis and percentages on the y-axis.

### Challenges and Difficulties Encountered
One of my biggest challenges was completing the COUNTIFS statements in the Outcomes Based on Goals Analysis. I feel we didn't cover much on this formula, and it was challenging to make sure to include all of the variables.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
- 1.Time of year really does impact the success of a campaign. According to our data, the months of "May" and "June" have the highest chance of meeting their fundraising goal, while months like November, December, and January (the colder months in America and Europe) all have a much lower chance of meeting their goal.
- 2.The summer months, like May, June, and July all seem to have higher chances for success rates on meeting their funraising goal. One thing I do notice in the dataset, is that the number of data points during these months is much higher too (more events go on during these months). I wonder if the lack of data outside of the summer months can skew the data slightly.

- What can you conclude about the Outcomes based on Goals?
-  Outcomes based on Goals analysis is that campaigns up to $5000 are the most successful. The second conclusion from this analysis is that campaigns of $45,000 and up are very unsuccessful.

- What are some limitations of this dataset?
- This dataset does not specify the genre of plays which would also allow us to see why some plays were successful or more popular over others. It would also be beneficial to see the publicity methods adopted by successful campaigns versus failed campaigns to see if there is a correlation there.

- What are some other possible tables and/or graphs that we could create?
- We could create a table that displays the genre of the play and then create a graph that shows the correlation of success rate based on the genre.
