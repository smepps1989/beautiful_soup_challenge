# beautiful_soup_challenge

Deliverables of this challenge include using Beautiful Soup to scrape a website containing news about Mars and information about weather on Mars.

Beautiul soup objects created to extract the titles and summaries from these news articles allowed for quick review of what was reported on for this topic.

The second part of this exploration involved analyzing data collected from this webpage after storing the scraped data into a dataframe with Pandas.

It was found that there are 12 months in a Martian year according to the collected data, with a total of 1,867 Martian days of data collected.

The chart below represents the average temperature by Martian month.

<img src="/Resources/images/avg_temp.png" width=75% height=75%>

The warmest Martian month appears to be month 8 while the coldest month appears to be Month 3.

This chart represents the average atmospheric pressure by month on Mars for the days collected.

<img src="/Resources/images/avg_pressure.png" width=75% height=75%>

To find the number of terrestrial days in a Martian year, the dates of data were grouped by month. Assuming that the data were documented in chronological order and with the knowledge that a full Martian year is 12 months, the minimum date of each month corresponds to the first terrestrial year of the data collected. This was found to be 8-16-2012, or the sixth month in a martian year. <br/>

Since this was the sixth month, the first full Martian year's worth of data would be completed in month 5. Therefore, the end of that year was calculated by using the minimum date for month 5 (found to be 2014-04-23) and looking to see when the month switched from 5 to 6, indicating that a new Martian year was beginning. That date was found to be 6-23-2014. This resulted in finding that the length of a Martian year is 676 terrestrial days.

The Mars DataFrame that was created after scraping the table holding the Mars weather data was then exported into a .CSV file for use for further exploration by other means.
