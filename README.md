# bikesharing

## Background:

> This project uses Tableau to visualize bike-sharing data.

> Kate suggests that you use Citi Bike data that has been released to the public for your analysis. You agree, but then remind her that you must be cautious when looking at the data, as it applies specifically to New York City—Des Moines is quite different!

> Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would
like to see a bike trip analysis.

**Language**: Python

**Library**: Pandas

**Software**: Tableau public

**Story Link**: [link to story](https://public.tableau.com/app/profile/b5363/viz/city_bike_1_2_3/CityBikeTrends)

____________________________________________________________________________________________

The goal of this project is to create visualizations that can be easily understood without any explanation.  Investors may or may not have a technical background to understand the data, so visualizations are a great way for a larger audience to understand what you are presenting to them.  Good visualizations are an essential tool for potential investors. 

### Overview of the analysis:

In the context of this case study, we are trying to create visualizations of bike sharing data of New York City.  Our colleague would like to replicate this bike service in Des Moines, Iowa.  Before we perform a hypothetical analysis of Des Moines, Iowa; it would be good to understand the costs and profit of the bike share service in New York City.  If the margins are slim, it may not make much sense to open this service in Des Moines, Iowa from a profitability standpoint.  Investors are less likely to invest in a business where they would likely break even. 

### Results:

Figure 1: 

![Customer Type](/Images/customer_base.png)

The first visualization is to understand the customer base of Citibike users in New York City. This is an essential visualization to understand potential profits. The majority of the customer base is subscribers.  Companies sometimes discount services for subscribers.  

Figure 2: 

![Starting Points](/Images/Top_starting_points.png)

The second visualization would be the top starting locations in New York City. This information could help us pick the best potential bike spots in Des Moines, Iowa.  This will require more research as the OpenStreetMap used didn't provide locational information.  Maybe we find out that in front of apartments/condos are one of the better spots. Another good spot could be in front of restaurants and bars.  

Figure 3: 

![Peak Hours](/Images/peak_hours.png)

The third visualization would be for the peak hours for Citibike service in New York City. This will help the team determine when to do repairs or swap in other bikes based on how many users are using the service.  The populated hours tend to coincide with typical working hours.  The most populated hours are after work until about dinner time.

Figure 4: 

![Typical length of a bike ride](/Images/length_of_trip.png)

The fourth visualization helps us to determine the typical length of a user using the Citibike service.  Most users use the service for only 5 minutes.  If users are only using the service for short durations, there will need to be a large user base to remain profitable.  

Figure 5: 

![Typical length of a bike ride by gender](/Images/length_of_trip_by_gender.png)

The fifth visualization helps us to determine the typical length of a user using the Citibike service by gender.  Males are the most frequent user of the service.

The previous two visualizations are helpful to understand how long the customers are using the service. This can vary by city to city if buildings are more or less spread out.  This will vary how long users use the service.

Figure 6: 

![Quantity of riders](/Images/heat_map_1.png)

The sixth visualization helps us to determine the quantity of Citibike users throughout the day.  The most populated hours of service is typically from five to seven pm on a weekday. Eight am seems to be a popular time for people to go to work on a weekday.

Figure 7: 

![Quantity of riders](/Images/heat_map_2.png)

The seventh visualization helps us to determine the quantity of users by gender.  Males are the most frequent users of the service during these populated times.

Figure 8: 

![Quantity of riders on all days by user type and gender](/Images/heat_map_3.png)

The eighth visualization helps us to determine the quantity of users by user type and gender.  As previously discussed, the majority of users are subscribers.  In this case, both males and females have more subscribers than customers.  It is interesting to note that there are more unknowns in customers than subscribers user type.  I imagine that this can be related to people who know they may use the service infrequently or ever again (travelers) do not want to give up that personal piece of information.   

The previous three visualizations are helpful to understand how many riders are using the service throughout the given day. Population of a city is likely a factor to consider in the numbers of riders in any given city.  

### Summary:

A successful bike sharing service will best thrive in metropolitan area.  It requires a large population that doesn't depend on cars as their primary form of transportation.  This is in part due to the proximity of major points of interest to the customer.  The majority of rides are less than 20 minutes. This isn't necessarily a drawback so long as there is a large enough population to support the service.  The type of the user also plays a big role in terms of profits.  Typically rides are incentivized for subscribers versus customers.  You will need a large subscriber base to justify the discounts that the subscribers receive for their loyalty to the company.

#### Visualization Extra 1

A visualization of preferences for city transportation.  This would likely vary significantly from city to city. New York has a popular subway system.

#### Visualization Extra 2

A visualization of number of rides by bike number per day.  Are there bikes getting used more than others? Is that due to location? Is one bike damaged, but yet to be reported? This visualization would help to determine which bikes need service first. 

