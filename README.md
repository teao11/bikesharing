# bikesharing

## Overview of the Statistical Analysis
This module challenge was designed for us to showcase the skills we had learnt with Tableau. We were supporting our team mates by creating an analysis on bike use in New York City for August 2019. Using the analysis and visualizations, we could make assumptions on how a potential bike share app would work in Des Moines, Iowa.

Visualizations were to be created and put into a Tableau story to be presented to investors and other interested parties.

## Results
Please find the Tableau story [hyperlinked here](https://public.tableau.com/app/profile/harry.morton/viz/HarryMorton-NYCCityBikeAnalysisAug2019/NYCCitiBikeStory?publish=yes).

Using Tableau, we were able to create the following visualizations and conclusions:

### Trip Duration by Hour of Day

<img width="776" alt="Screen Shot 2021-08-29 at 12 57 03 PM" src="https://user-images.githubusercontent.com/46773181/131263685-d6cae1e7-a928-4137-8328-799d6f46835c.png">

The visualization above shows that the overwhelming majority of bike trips are short (within 20 minutes). This could suggest that bikes should be placed strategically in locations where driving is not an option (congested area, FiDi's) as longer trips are likely being taken by car.

### Trip Duration by Hour of Day by Gender

<img width="765" alt="Screen Shot 2021-08-29 at 1 00 31 PM" src="https://user-images.githubusercontent.com/46773181/131263775-0c9f5ded-c8e8-4a3d-b5a3-f60c0c3f8cec.png">

The visualization above layers on gender as an additional segmentation to the trip duration visualization. We see that although men utilize the bikes far more than women or unknown, they follow the same trends (moajority of rides less than one hour).

Here we get additional insight as to the use of bikes for men vs. women. Are men the main target market for these bikes? Or is this limited purely to NYC.

### Trips by Weekday per Hour

<img width="786" alt="Screen Shot 2021-08-29 at 1 03 11 PM" src="https://user-images.githubusercontent.com/46773181/131263855-8982b86a-a06c-45d8-9909-8eb8c396b11c.png">

We see in this visualization, a heatmap of trips by hour and weekday. Not suprisingly, through the week the most popular hours are when folks would be commuting (morning and evenings). On the weekend, the volume of trips is more evenly distributed throughout the day.

One interesting question would be whether the locations are similar for weekdays vs. weekends -- this could be used to maximize trip count by moving bikes on Friday nights to locations that are most popular on the weekends.

### Trips by Weekday per Hour (by Gender)

<img width="1010" alt="Screen Shot 2021-08-29 at 1 06 48 PM" src="https://user-images.githubusercontent.com/46773181/131263945-c9da7852-b838-4dcb-b959-5040c47c22df.png">

Here we see that both genders utilize the bikes at similar hours (trend holds true to the previous visualization). However we again see the difference in usage for men vs. women.

### User Trips by Gender by Weekday

<img width="764" alt="Screen Shot 2021-08-29 at 1 08 24 PM" src="https://user-images.githubusercontent.com/46773181/131263983-40aba6c7-a56a-4ecd-8321-e3d10df8c034.png">

Analyzing the usage by trips by weekday, we see that subscribers use the bikes more than customers. Through the week, Thursday's seem to be the most popular day whilst Wednesday usage almost mirrors that of the weekends.

### Top Starting Locations

<img width="1004" alt="Screen Shot 2021-08-29 at 1 11 42 PM" src="https://user-images.githubusercontent.com/46773181/131264049-8a137c9f-b7ea-439a-b58e-f18dd2dc811e.png">

We see the most popular locations to start a bike ride are concentrated towards the lower east side, which makes sense given our understanding of population density and office location. Comparing to the following visualization helps round out our understanding of trip length:

### Top Ending Locations

<img width="1002" alt="Screen Shot 2021-08-29 at 1 13 15 PM" src="https://user-images.githubusercontent.com/46773181/131264081-ce076460-283b-43c4-a150-5a51f7304c3f.png">

The ending locations really line up with the starting locations, indicating that trips are not that long in distance. This reflects the conclusion drawn from the first visualization, as shorter trips generally mean shorter distances travelled.

## Summary

In conclusion, if we are to use NYC as a model to understand success in Des Moines, we saw:
- Men are the power users of these bikes
- There are very clear times that bikes are used, differing on weekends vs. weekdays
- The majority of trips are ~20 minutes, and are concentrated to areas with high population density / office concentration and sub-optimal driving routes

However, there are some things that we should consider before drawing conclusions and applying them to Iowa:
- How similar is NYC to Des Moines in terms of traffic / office density / population density? If they are different, is there a better similar we can analyze?
- This analysis was only conducted using August 2019 data. How does the weather affect NYC citi bike usage (winter / fall / spring)?
- Does Des Moines weather mirror NYC?

Answering these questions would help us make better decisions.
