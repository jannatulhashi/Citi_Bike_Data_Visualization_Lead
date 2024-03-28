# Citi Bike Data Visualization Using Tableau
Analyze and visualize New York Citi Bike data to deliver insights on ridership and station usage,
enabling city officials to make informed decisions for the city program's enhancement using Tableau.

## Background

![](Images/citi-bike-station-bikes.jpg)

As the new lead analyst for the New York Citi Bike program, I am now responsible for overseeing the largest bike-sharing program in the United States. In my new role, I will be expected to generate regular reports for city officials looking to publicize and improve the city program.
Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the [Citi Bike Data](https://citibikenyc.com/system-data).
However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so my first task on the job is to build a set of data reports to provide the answers.

### Instructions
My task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find unexpected phenomena.
1: Design 2–5 visualizations for each discovered phenomenon (4–10 total). I have the flexibility to work within a timespan of my preference. If needed, I can also combine multiple datasets from various periods.
Here are some questions I might want to address:

**Dashboard 1:** Ridership Growth and Patterns
Visualization 1: Yearly Ridership Count by Station and User Type:
- Which station consistently sees the highest ridership, and does user type (member vs. casual) influence this trend?
Visualization 2: Yearly Ridership Count by User and Rideable Type:
- How does the preference for rideable type differ between regular and casual users over the years?
  Visualization 3: Weekly Ridership Count by User Type Over the Years:
- Is there a specific week or time of year where we see a spike in ridership among casual users compared to members?

![](Images/Dashboard_1.png)

**Analysis:**

**Yearly Ridership Count by Station and User Type:** This visualization brings forth the stations that are most frequented. If certain stations consistently have high ridership irrespective of user type, they might be located in commercial areas, tourist spots, or transport hubs. Conversely, stations with lower counts may indicate areas that could benefit from marketing efforts or infrastructure improvements.

**Yearly Ridership Count by User and Rideable Type:** Noticing trends in which types of bikes are preferred can help in inventory decisions. An increasing preference for one type might indicate changing urban dynamics or rider preferences.

**Weekly Ridership Count by User Type Over the Years:** Fluctuations here can showcase seasonality, the effectiveness of promotional campaigns, or external events affecting ridership. Regular spikes could indicate weekday commuters, while weekend peaks might suggest leisure riders.

**Dashboard 2:** Station Popularity and Ride Characteristics
Visualization 1: Top 10 Starting Stations by Ride Count, Differentiated by User Type:
- Which starting station is the most popular among casual users, and how does that compare to members' preferences?
Visualization 2: Top 10 Ending Stations by Ride Count, Differentiated by User Type:
- Are there any ending stations that are significantly more favored by members than by casual riders?
Visualization 3: Average Distance Traveled in Miles:
- What's the typical distance that both user types prefer to travel on their rides?

![](Images/Dashboard_2.png)

**Analysis:**

This dashboard offers insights into the most popular stations and the characteristics of the rides originating from them.

**Top 10 Starting Stations by Ride Count, Differentiated by User Type:** Observing which stations have the highest starting counts can help in resource allocation, ensuring there are enough bikes available. Differences between member and casual users can give insights into commuting patterns vs. tourist attractions.

**Top 10 Ending Stations by Ride Count, Differentiated by User Type:** Stations with high ending counts may need larger docking areas or more frequent maintenance checks.

**Average Distance Traveled in Miles:** This can inform about the typical use-case scenarios. Shorter distances might imply usage for errands or intra-city travel, while longer distances could suggest recreational use or lack of public transport options.

**Dashboard 3:** Bike Utility and User Behavior
Visualization 1: Average Trip Duration by User Type and Rideable Type:
- Do regular members tend to ride for longer durations than casual riders on specific rideable types?
Visualization 2: Top 20 Most Ridden Bikes by Distance (in Miles) Between Stations:
- Which specific bike has traveled the furthest distance overall, and does its route preference indicate a trend?
Visualization 3: Daily Ride Counts by July 2022 - July 2023:
- Were there any notable daily spikes in rides between July 2022 and July 2023, and if so, what might have caused them?

![](Images/Dashboard_3.png)

**Analysis:**
This dashboard dives deep into how bikes are utilized and the behavioral patterns of users.

**Average Trip Duration by User Type and Rideable Type:** Observing how long bikes are usually rented can give insights into the nature of trips. Members might have shorter, more consistent durations (commuting), while casual users might have longer, more varied durations (exploratory rides). The outlier with casual users on docked bikes having a longer average trip duration might indicate leisurely rides, tourists taking scenic routes, or unfamiliarity with the city's bike routes. Members might have shorter durations as they use bikes for specific purposes like commuting.

**Top 20 Most Ridden Bikes by Distance (in Miles) Between Stations:** Bikes that are frequently used may require more frequent maintenance. Tracking these can also offer insights into the efficiency and popularity of specific bike models or types.

**Daily Ride Counts by July 2022-July 2023:** Understanding day-to-day variations can inform daily operations, including resource allocation and predictive maintenance.

2: Create the following visualizations for city officials:

**Map 1:** Popular Starting Bike Stations by Ride Count
- Which geographic region of the city consistently serves as the most popular starting point for riders?

![](Images/Dashboard_4.png)

**Analysis:**

**Spatial Distribution:** Certain regions, possibly commercial or urban hubs, have elevated ride counts.

**Rideable Preferences:** Some zones display preferences for specific bike types, perhaps due to user demographics or local terrain.

**Station Popularity:** Larger visualized stations experience more frequent usage, suggesting they're critical for the city's mobility.

**User Types:** A significant number of rides are initiated by members, indicating a strong local user base and potentially regular commutes.

**Visualization Clarity:** The diverse color palette for stations ensures easy differentiation and understanding of ride activities.

**Map 2:** Popular Ending Bike Stations by Ride Count
- Are there any areas in the city where rides tend to end more frequently, perhaps indicating popular destinations or points of interest?

![](Images/Dashboard_5.png)

**Analysis:**

**Favored Spots:** There are specific stations where riders predominantly choose to end their journeys. These stations might be located near prominent landmarks, commercial centers, or residential areas.

**User Behavior:** A visible distinction between members and casual users at certain end stations may hint at areas preferred by daily commuters versus occasional riders or tourists.

**Consistent Choice:** Despite having various bike options available, classic bikes seem to be the preferred choice for most riders in the dataset. This could indicate their reliability, comfort, or general popularity among the user base.

**Route Popularity:** By observing the endpoints, we can infer some of the most popular routes or destinations for classic bike riders.

**Map 3:** Dynamic Popularity of Bike Stations Over Time
- How have the popular bike stations shifted between July 2022 and July 2023, and can we attribute this shift to any specific city developments or events?

![](Images/Dashboard_6.png)

**Analysis:**

**Hot Spots:** Some stations are consistently busy, serving as key points in the bike-sharing network. Their size and color on the map make them easy to spot.

**Year-on-Year Growth:** Comparing the two Julys, we notice some stations experiencing a rise in popularity, while others might have a reduced footfall. Such trends can arise from various urban factors like new infrastructure, changes in traffic patterns, or even emerging local attractions.

**User Types:** A fascinating point is the balanced distribution between members and casual riders in both years. It's evident that the service attracts both regular and occasional riders.

**Favorite Bike Type:** Classic bikes are overwhelmingly the most popular. If we like these bikes, chances are we'll find them at most stations.

Finally, I created my final presentation using Tableau:

[Created a Tableau story that brings together the visualizations, requested maps, and dashboards](https://public.tableau.com/app/profile/jannatul.hashi/viz/MyFirstViz_16938834061370/Story1)
