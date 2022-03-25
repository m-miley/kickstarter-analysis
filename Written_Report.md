# Kickstarting with Excel

## Overview of Project
Using Excel and the provided clean data set, we will build an analysis using charts, graphs, and pivot tables to communicate important insights.
### Purpose
The purpose of this analysis is to provide Louise with explanations to how different campaigns performed in relation to their launch dates and funding goals.
## Analysis and Challenges
Louise should heavily consider launching her campaign in May or June so that she can maximize the potential for meeting her goal.  Using a pivot table and line chart, and selecting the outcomes and launch date fields, we could quickly and easily interpret the results in the following image.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/100544761/159764488-5fb27f81-3701-4e58-baa9-52b9b0203b2d.png)

Furthermore, with a goal of $15,000 or under, she would most likely succeed.  Also, the $35000 to $45,000 range for a goal is mentionable, however there are other factors likely at play that we could research given the proper data and time. For this analysis, we created $5k intervals to group the count of outcomes by so that we may compare results.  This allowed us to easily interpret the chart to make suggestions on goal amount.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/100544761/159766568-8fb27e48-b1f8-4c4a-b825-a04c20a9d81b.png)

Potential difficulties ly in detail.  It is very important to ensure selecting the right rows/columns/cells when inputing a function.  Nesting functions shold be written carefully.  Ensuring that the proper filters are applied and cleared when linked to a chart.  This is a very clean data set, however, further challenges would include cleaning the data and maintaining integrity, properyly handling NULL values, outliers, interpreting field headings, duplicates, etc.  Further difficulty could be confronted with numerous column headings and keeping everything organized.

## Results

### Analysis of Outcomes Based on Launch Date
- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. Clearly the top 3 most successful launch months for theater kickstarter campaigns fall in May, June, and July, respectively.
    2. Each month saw more successes than failures and cancellatioins were relatively low consistently throughout the year.

### Analysis of Outcomes Based on Goals
- What can you conclude about the Outcomes based on Goals?
    Success and failure is inversely related in respect to outcome counts. We see a spike in failures and likewise diminishing success in the $20,000 to $35,000 range, as well as $45,000 and above for goals.  Otherwise, successes outweigh failures in all other dollar ranges, i.e. $0-$20k and $35k-$45k.

### Challenges and Difficulties Encountered
    See above analysis and challenges section.

### Limitations
- What are some limitations of this dataset?
    It's a fairly small data set.  Statistical significance would increase and be potentially more predictive or reliable if the sample size was larger, particularly considering that there are only 21 participating countries with limited sample sizes and limited participation in each or a few categories at best.  There are is no specific data as to what types or genres comprise each subcategory such as plays and musicals. Location for backers or more information about them could be helpful. There's no data on strategies to achieving goals or outreach to collecting pledges or marketing.

### Other possible tables and graphs
- What are some other possible tables and/or graphs that we could create?
    Sum of pledges for each category/subcategory and average the donation amount to provide Louise with an expectation for donations.  We could create a histogram that shows the frequency of donations by bins of 20 or so.  We can create a column of days_to_deadline to see if higher amount of days to collect pledges correlates to the outcome or success rate and/or provides a higher dollar amount.  We can create charts to see which years/quarters have the highest success rate.  Sum of backers for each category/subcategory could be helpful as well.  Average Percentage funded for each category/subcategory overall.  We should/could include a box and whiskers chart in case there was question about outliers and statistical integrity.

    