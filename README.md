# PyBer_Analysis  - Use the PyBer ipynb file to use additional chart info

## Overview of the analysis:

PyBer is a Python based ride sharing app company and I have been fortunate enough to start a new Data Analyst role at PyBer.  My first project is to analyze ride sharing data and recommend ways to improve access and affordability of rides to drive profitability of the company.  I have been provided with two seperate csv files with one containing information about rides and cities and one containing information about rides and drivers.  The csv files were loaded into jupyter notebook and merged together by city to start the analysis.  The data was broken out into the city types of Urban, Suburban, and Rural so that information about each area can be analyzed.

## Results:

The results of the analysis shows that there were a total of 2,375 rides.  Rural had 125 rides, Suburban had 625 rides, and Urban had 1,625 rides.  The following pie chart shows the percentage breakdown of rides per city type:

![Rides_by_City_Type](https://user-images.githubusercontent.com/107599510/182698287-204ec6e9-57de-4af0-94c7-c73fa197339e.png)

When looking at the total fares by city type, it is no surprise that the percentage of fares follows a similar distribution as the number of rides per city type:

![Fares_by_City_Type](https://user-images.githubusercontent.com/107599510/182699169-6be1b07b-992e-403e-99a1-6ce1f07e1133.png)

This pie chart shows the percentage of total drivers by city type:

![Drivers_by_Type](https://user-images.githubusercontent.com/107599510/182716944-dbbd9625-a26c-464e-8f33-79c58f4b90f0.png)

The data was also plotted on a scatterplot in order to help with visualization and analysis of the data.  The following graph shows the results:

![Scatterplot](https://user-images.githubusercontent.com/107599510/182699727-f84d6bab-59dc-49ed-abb2-597bfbdfe122.png)

The data from the scatterplot provides a visual breakdown of number of rides as well as average fare per city for those rides.  Additionally, the circle size correlates with driver count per city.  The results from this are pretty similar to what one would expect when providing rides for three different types of cities.  The mean fare for an Urban ride is $24.53, Suburban is $30.97, and Rural fares average $34.62 per ride.

The Urban areas have more rides, more drivers, and lower average fares.  Rural areas have less rides, less drivers, and higher average fares.  This makes sense to me as Urban areas have larger populations and a ride in an urban location would consist of shorter distances.  This equates to more ride opportunities and but also lower fares due to shorter driving time and distances.  The scatterplot shows that a ride from a rural area does not have the same demand as Urban areas.  However, due to an increase in driving distnace and time the average fares are higher.  Suburban number of rides and average fares fall somewehre inbetween Urban and Rural.  Logically this makes sense due to factors mentioned above relating to driving time and population.

The final visualization was performed to review ride information over a 4 month period.  The data falls in line with the previous analysis:

![PyBer_fare_summary](https://user-images.githubusercontent.com/107599510/182706383-0b2bdc71-d469-4790-b4dd-406cc4f10e49.png)

The data on this chart show the relationship between fares by city type as well as the amount of fares earned for each city type.  The chart shows Urban leading the way with Suburban in the middle and Rural with the fewest rides and fares earned.  There are some spikes in rides for all three types between February and March.  At a glace, there could have been a big social event like a concert or fair during that time that drove the demand.  More data would be needed to determine the case for the spike in all three city types.  After that, there are a few spikes in fares earned that do no appear to not correlate with the other city types. Let's move to the summary to see if the data can provide insights in how to dive availability and profitability for PyBer. 

## Summary: Provide a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types.

For PyBer, the Urban city type provides the most volume and most revenue of the three city types.  While this news is not shocking, one might ask what changes can be made to improve the best part of your business?  My recommendation to the CEO would be to analyze city data during peaks and valleys in the ride demand.  Try to understand where the rides are coming from and going to.  The key to unlocking the ride potential for each city is to understand the events and resources each city currently has in place.  Museums and tourist attractions in cities provide an opportunity to market or partner with the attractions to increase ride share in that city.  If a city has a social district or festivals, advertising or partnering with local bars and having drivers nearby the events will increase the opportunity for increasing rides.  The key here is to learn what PyBer is already doing well and get to know each city to take advantage of existing opportunities to provide rides.

The Suburban ride share makes up 26.3% of total rides for the company.  My recommendation would be to learn about the cities in which we operate and identify which ones have an airport.  If a city has an airport, I would recommend partnering with the airport to become the official ride share company to get people to and from their flights and to their hotels.  Another big opportunity would be to understand the events calendar for that city and advertise rides to and from the events.  This will provide people a safe way to enjoy the event and get home afterwards if they have been drinking at the event.  

The rural city type for PyBer is the most interesting.  The total rides in the Rural area represents only 5.3% and 2.6% of total number of drivers.  The data provided here could have an Executive look at this data and think one of two things.  The first thought would be to just get rid of this service as it is not providing enough rides and focus on Urban and Suburban business.  A more business savvy executive would look at the small ride share as an opportunity for growth.  How can we turn the smaller ride shares in Rural areas into an opportunity?  I'm glad you asked.  As with the Urban and Suburban city types, it will be worth it to dive further into the ride sharing data to understand where our customers are getting rides from and where they are going.  The key thing to remember from the data is that even though Rural represents 5.3% of total rides, the rides average $34.62 per ride compared to $30.97 for Suburban and $24.53 for Urban rides.  Based on those numbers, 3 rural rides would generate $103.86 in fare revenue while it would take 4 urban rides to generate $98.12 in fare revenue.  A small increase in rural rides will result in faster growing fare revenue while using the fewest amount of drivers of all the city types.  A fair, carnival, or concert provides opportunities in each rural area to increase the number of rides and increase fare revenues.

In summary, I beleive it would be to PyBer's advantage to review each city type to understand how their service is currently being used to improve each business line.  This also provides an opportunity to get to know more about each community and their attractions to determine how to market services and who to partner with to increase ride shares in each area.  The bulk of the business comes from Urban and Suburban rides but don't neglect the Rural areas.  A small increase in rides in these areas will lead to a bigger impact on revenue for the company due to the average price per ride being the highest of the three city types.

