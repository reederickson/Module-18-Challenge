# Module 18 Challenge
[Tableau Public Workbook](https://public.tableau.com/app/profile/reed.erickson/viz/Module18Challenge_17102038717520/LengthofTripVStartingLocation)
# Exploring Trip Length, Starting Locations, and Temporal Trends in Citi Bike Data

The analysis of trip length, starting locations, and time-based trends in the Citi Bike dataset provides valuable insights into user behavior, spatial patterns, and temporal dynamics within the bike-sharing program in New York City. By visualizing these factors, we can uncover trends that inform operational decisions and enhance the overall program experience.

## Insights from Visualization:

### Trip Length Distribution:

* The histogram illustrates the distribution of trip lengths, revealing common durations of bike rides. Peaks in the histogram indicate prevalent trip lengths, suggesting typical user preferences and usage patterns.
* Notably, there is an outlier with an exceptionally long trip duration, indicating unusual usage behavior that warrants further investigation.

### Starting Location Analysis:

* The map overlay identifies Grove St Park as the most common starting location for bike trips, indicating a high demand for bike-sharing services in this area.
* Surprisingly, there are no bike trips originating from Staten Island, suggesting over accumulation of bikes ending their trip here, 
### Relationship Between Trip Length and Starting Location:
* The scatter plot demonstrates the relationship between trip length and starting location, highlighting spatial trends and correlations.
* Although NJCYU is not the furthest bike station location, it recorded the longest trip duration, indicating factors beyond proximity influencing trip lengths.

### Ending Location Analysis:

* Examination of ending locations reveals spatial patterns in trip destinations. Identifying frequently used end points can inform station placement and infrastructure development.
* Analysis may uncover popular destinations or commuter routes, facilitating targeted interventions to improve user experience and optimize bike availability.

### Relationship Between Trip Length and Starting/Ending Locations:

* The scatter plot demonstrates the relationship between trip length and starting or ending location, highlighting spatial trends and correlations.
* Clusters of data points may indicate areas where longer or shorter trips are more common

## Temporal Trends:

* The peak of bike starts at 8 am suggests a correlation with typical work commute times, indicating that the bike-sharing program is utilized by commuters.
* Longest trips occur on Saturdays, while the shortest trips are on Fridays, reflecting differing usage patterns on weekdays versus weekends.

## Average Trip Duration vs. Time of Day:

* Female riders exhibit longer average trip durations at 5 am, potentially indicating early morning recreational or exercise rides.
* A spike in average trip durations is observed between 1 pm and 6 pm, suggesting extended leisure or commuting trips during these hours.

### Outlier Identification:

* An outlier with an average trip length of 1,925 seconds (approximately 32 minutes) for a female rider born in 1946 raises concerns about data accuracy. Given the rider's age in 2015 would be 91, such a long trip duration is highly unlikely and may indicate data entry errors or anomalies.


### Conclusion
Overall, there are far more Customers than Subscribers, and this makes sense because you can have repete customers. This becomes an issue in analyzing the data because, unlike subscribers, customers do not have to share data like gender or age. I find it better to analyze the most popular times and days of the subscribers to avoid duplicate riders.

The visualization "Length of Trip vs. Starting Location" offers valuable insights into trip duration, spatial patterns, and temporal trends within the Citi Bike program. By examining these factors, stakeholders can gain a deeper understanding of user behavior and usage dynamics, facilitating data-driven decision-making to optimize program operations and enhance user experience. Further analysis and exploration of these insights will contribute to the ongoing success and evolution of the Citi Bike program in serving the diverse needs of New York City residents and visitors.

