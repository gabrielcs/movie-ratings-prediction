# Regression Project MVP

## Goals

A non-profit organization is trying to raise awareness about women in technology. We need to identify the best areas to canvas. The organization will be placing street teams at the enxtrances to various subway stations.

## Initial Data Cleaning Approach and Exploratory Findings

I examined the turnstile data available on the MTA website. The turnstile data only provided the cumulative number of entries and exits, not the net amount for any particular time period. I used a Python loop function to go through the data and calculate the net entries for each period.

The MTA collected most of its turnstile data at regular, four-hour intervals of midnight, 4am, 8am, etc. However, there were many instances where the data was an hour off of the regular schedule, and some observation times were seemingly random. To help with my time analysis, I rounded all time periods to the nearest hour, and eliminated the small proportion of data that far removed from the regular schedule.

After cleaning the data, I was able to further narrow my station targets to 15, based on the total traffic for the month of December 2016.

![Top Stations Graph](images/top15.jpg)

There is variability on stations by the day of the week.

![Day of Week Variability](images/weekly_var.jpg)

There is strong variability on stations by the time of the day.

![Time of Day Variability](images/day_var.jpg)

## Intial Research Findings

1. **Time of Day** - People are more receptive to talking and listening to new ideas depending on the time of day. During the morning and evening rush hour, people are concerned with getting to work or getting back to their family. Off-shoulder times such as mid-to-late afternoon when people are in a more relaxed mood has shown to be better.
2. **Audience Matters** - The type of person you talk to can greatly vary the outcome of a canvassing project. Finding open-minded people is not easy. Preliminary research suggests college students are the most receptive to new ideas and ready to ask questions. Though, whether they follow through and engage with the non-profit is another story.

## Further Research and Analysis

1. Income, Volunteerism and Charitable Giving
2. Technology Hubs
