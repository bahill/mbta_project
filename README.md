## MBTA Project
Uses the [MBTA APIs](https://api-v3.mbta.com/docs/swagger/index.html)
to provide the following information:
- All “subway” (light & heavy rail) route long-names
- The name of the subway route with the most stops as well as a count of its stops
- The name of the subway route with the fewest stops as well as a count of its stops
- A list of the stops that connect two or more subway routes along with the relevant
route names for each of those stops.
- Given a 2 stops (provided by a user), a list of the rail routes you would travel to get from one stop to the other 