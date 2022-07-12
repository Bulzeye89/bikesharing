# NYC Citibike Challenge

## Overview 

### Purpose
The purpose of this analysis is to give potential investors insights into a bikesharing program, CitiBike, based out of New York City.  They are looking to see if if it would be profitable to start a similar bikesharing program in the city of Des Moines, IA.  Looking at a data from August of 2019 will provide some insight for the business proposal.  
  

### Tabelau Public Story 
[NYC Citibike Challenge - Tableau Public](https://public.tableau.com/app/profile/scott.miller6682/viz/Bulzeye89NYCCitibikeChallenge/NYCCitiBikeStory?publish=yes)


## Results
For the purpose of this analysis, NYC citibike data from August of 2019 was used from a csv file.  Unfortunately, the file was too large to upload here.  The data was initially cleaned up by loading it into a jupyter timebook and converting the tripduration column from an integer datatype to a date time datatype.  This [ipynb file](https://github.com/Bulzeye89/bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb) can be found here. From here, the data was uploaded to Tableau for further analysis and the rendering of the below charts.  


The NYC data reveals a rather large portion of the trips are taken by male subscribers.  
<p>
<img src="https://github.com/Bulzeye89/bikesharing/blob/main/Resources/Charts/User_Trips_by_Gender_by_Weekday.png">
</p>

<br>
<br>

Majority of trips are under 20 minutes with very little percentage of trips lasting more than 40 minutes.  This could be due to time restrictions placed on bike usage where people are trying to avoid higher or extra charges.  
<p float="left">
<img src="https://github.com/Bulzeye89/bikesharing/blob/main/Resources/Charts/Checkout_Times_for_Users.png" width=49% height=50%>
<img src="https://github.com/Bulzeye89/bikesharing/blob/main/Resources/Charts/Checkout_Times_by_Gender.png" width=49% height=50%>
</p>

<br>
<br>

The data reflects that the majority of of trips started and ended in higher tourist and commuter areas where more residential areas had lower instances of starting and ending trips.  
<p float="left">
<img src="https://github.com/Bulzeye89/bikesharing/blob/main/Resources/Charts/Top_Starting_Locations.png" width=49% height=50%>
<img src="https://github.com/Bulzeye89/bikesharing/blob/main/Resources/Charts/Top_Ending_Locations.png" width=49% height=50%>
</p>

<br>
<br>
This heatmap below of times when trips were initiated further supports the commuter usage. 
<br>
<img src="https://github.com/Bulzeye89/bikesharing/blob/main/Resources/Charts/Trips_by_Weekday_per_Hour.png">
<br>
<br>

Keeping with the gender analysis, the below heat map shows times for trips for male and female users show no huge variance.
<br>
<img src="https://github.com/Bulzeye89/bikesharing/blob/main/Resources/Charts/Trips_by_Gender_weekday_per_Hour.png">
<br>
<br>

Regular maintenance and repairs must be part of the budget plan.  Bikes in the higher usage areas will need to be cycled in and out.
<br>
<img src="https://github.com/Bulzeye89/bikesharing/blob/main/Resources/Charts/Bike_Repairs.png">
<br>
<br>

With this in mind and in an effort to minimize any disruption to the bike sharing services/availability, the hours between 2am and 5am seem to be the most ideal time for scheduled maintenance.
<br>
<img src="https://github.com/Bulzeye89/bikesharing/blob/main/Resources/Charts/August_Peak_Hours.png">
<br>
<br>



## Summary: 
To summarize, the data for August 2019 from the NYC citibike sharing program indicates that the user base leans heavily male and subsription based.  This bodes well for projected revenue projections as subscriptions are more predictable streams.  The evidence also shows credence that heavy trip times are focused around commuting hours as well as the busier downtown locations.  It would be interesting to see the citibike subscription based program and if there are time limits based on usage to avoid incurring extra fees.  Any potential program should take into account regular scheduled maintenance and plan it during off-peak hours.  Further research should be looked at which stations have the most trips started and ended per customer types.  Subscribers, while more predictable revenue, is often less profitable, than the "regular" customer who is more likely to be a tourist and willing to pay more.  Identifitying the most popular stations for these types of "regular" customers to ensure more bikes are readily available.  It would also be very interesting to look further into the demographics by age.  Doing this could really help identify the target market for when a program is launched into a new city.  Some updated data would also be extremely useful so comparisons can be made pre and post Covid and see if any significant changed happened due to people working from home or from people avoiding public transport.  
