# Kickstarting with Excel

## Overview of Project

Use Kickstarter data to find trends in fundraising success, based on their launch date and fundraising goals

### Purpose

To extract relevant data from a Kickstarter fundraisers database to help future fundraisers be successful

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

A table was created to separate Kickstarters from the theater category into their monthly launch date. They were then categorized as successful, failed, or canceled.
https://github.com/J0HN-MAC/kickstarter-analysis/blob/a194c664125c004f223aaeed50b5118e67976fa9/Resources/Outcomes_Based_on_Launch_Date.png

### Analysis of Outcomes Based on Goals

From the plays subcategory, fundraisers were tallied according to their outcome (successful, failed, or canceled). These outcomes were also incrementally seperated according to their funraising goal.
https://github.com/J0HN-MAC/kickstarter-analysis/blob/main/Resources/Outcomes_vs_goals.png

### Challenges and Difficulties Encountered

No specific challenges or difficulties were encountered during . However, certain pervasive events (elections, economic events, wars, pandemics, etc.) could skew monthly data even if those events were isolated to particular years.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The most successful Kickstarters in the theater category were launched in May (111), followed by June (100) and July (87). December has not been a successful month as more theater fundraisers have either been canceled or failed (38 combined) than have been successful (37).


- What can you conclude about the Outcomes based on Goals?

The fundraisers with the smallest goals (up to $4,999) had the largest success rate. The success rate generally decreases as the goal increases. However, there was a sweet spot between the goals of $35,000 and $44,999 that had a success rate of 67%.

- What are some limitations of this dataset?

In the plays subcategory, there were no canceled fundraisers in the Kickstarter dataset. This could be a limitation of the dataset if there are reporting discrepancies with canceled fundraisers.

- What are some other possible tables and/or graphs that we could create?

It could be helpful to create scatter plots to identify outliers and examine how they are affecting this analysis.
