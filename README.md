# Fundraising Analysis 
## Overview 
Fever is a play that could not reach its fundraising goal previously, for that reason, Lousie would like to have a better understanding of what makes a fundraising campaing succesfull. For that reason, in the following analysis we will be looking closely at two different variables,goal amount, launch date and its relationship with the outcome of the fundraising.

## Analysis and Challenges 
### Overall Analysis 
To begin the analysis we took a look at the relationship between the lauhc date with the outcome, to obtain this data, the `=year` function was used to extract the time information from the launch date, later a `PivotTable` was created and filtrated by `months`, the parent category into `Theater` and arranged in `descendent`. At first glance, we can evidence that the failed and successful campaigns have a similar behavior, **except for the months May, June and July in which the successful outcomes increment significantly.**

The second analysis was the outcome according to the goal. First, the goal was segmented into different amounts with increments of $5000 per segment, allowing the data to have a better structure for the intended analysis.Later on, the formula `=countifs` was used to extract the information and filter was added, such as `plays` on the subcategory, `successful` on the outcome and the `amount` on the goal according to each segment. The results show that none of the plays were cancel, regardless of the goal amount, also,**there is an invert relationship between the successfull and failed overcome.** 

###Challenges 

The main challenge of this process was the `=countifs` formula and understandings its estrucuture, since each criteria has a separated criteria range. The second challenge was getting familiarized with the [github languaje]( https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax )

