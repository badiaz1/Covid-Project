# Covid-Projectn

# Goal:

COVID-19 was and still is a generation life altering event whose effects are still rippling through today. After coming across a public data set covering COVID-19 around the world, I wanted to know what kind of effects on a continent. I am from the North American continent so I thought somewhere the climate is completely different. Oceania, mainly the location of Australia.

We know with COVID restrictions being lifted I wanted to know what kind of effects it has had on the country and its death tolls. My hypothesis, although the new cases of COVID-19 will increase, the new death tolls will stay at a minimal or a slight increase. To evaluate this hypothesis I will be using Rstudio to further understand and evaluate the data. 

# Process:

I used Rstudio for my analysis to create a R markdown file that is outputted as an html.document file. The libraries used for this project are: tidyverse, readr, dplyr, stringr, and ggplot. 

I take the public csv. file and upload it to the markdown file using an r code chunk. First observations I see that there are 67 variables, so I then selected the variables that seemed most appropriate for what I wanted to observe. These variables included: continent, location, date, hosp_patients, new_deaths, total_deaths, people_vaccinated, total_boosters. I then filtered the data so that only the locations and the content data points are from oceania. After looking through the new data set. I see that there are some NA values for all the variables. I replaced locations that were labeled as Oceania as unknown because I am trying to look at the location of Australia so this will help with removing some outliers. I then saw that some of ‘continent’ cells had NA values so I replaced them with ‘Oceania’. For the variables people_vccinated, total_boosters, and new_deaths, and their missing numerical values. I was able to replace NA with 0. 

Once I created my data set to analyze, I was able to further manipulate the next data set to filter only the location of Australia and created a plot graph to show the new deaths throughout the years. Then narrowed my view to the effects of this past year. 

# Findings:

Looking at the graphs created, I see there has been a big spike of new deaths this past year. There was a slight increase at the end of 2021, their summer time. Then at the end of February, Australia reopens their borders to international travelers who are vaccinated. These effects can be seen in a rise in death tolls. 

# Conclusion:

Based on my findings in the data, I believe we should start to see a fall in the new deaths within the next year. Not only because the new vaccine counts continue to increase, but because we are allowed more human interactions again. With the stay at home order in place for about a year, has caused some people to be susceptible to other viruses other than COVID-19. The new deaths recorded include possible COVID related deaths; therefore, leaving room for human error and outliers. 
