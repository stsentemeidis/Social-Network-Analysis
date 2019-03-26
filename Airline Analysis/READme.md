We compare the respective networks of **American Airlines**, **Delta Air Lines**, and **United Airlines**.    
We have accessed a schedule dataset from *Innovata Schedules*, which lists all the flights scheduled in the calendar year of **2018** for each month.       

For each city pair, three metrics are given to establish the flight schedule: 
1. **number of flights** operated in the month
2. total **number of seats** available on the route for the whole month
3. **available seat miles** (Total number of seats available * distance of the route flown).

Network will be **non-directional**, as capacity dispatched by scheduled carriers is bi-directional and most customers buy round-trips.      

It will be **weighted** by the different capacity metrics detailed above.     

We will be able to examine which carrier has the most efficient network *(Low average path length)*, which airline is best equipped if a particular hub is affected by weather events *(Low centrality)*, and for large markets where all three carriers are competing, e.g. New York City or Los Angeles, establish which carrier is the most attractive for frequent flyers.
