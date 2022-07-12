# NYC Citibike Challenge

## Overview 

### Purpose
The purpose of this analysis is to give potential investors insights into a bikesharing program, CitiBike, based out of New York City.  They are looking to see if if it would be profitable to start a similar bikesharing program in the city of Des Moines, IA.  Looking at a data from August of 2019 will provide some insight for the business proposal.  
  

### Tabelau Public Story 
[link to dashboard](LINK GOES HERE "link to dashboard")


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


This heatmap below of times where trips were initiated further supports the commuter usage. 
<br>
<br>
<img src="https://github.com/Bulzeye89/bikesharing/blob/main/Resources/Charts/Trips_by_Weekday_per_Hour.png">
<br>
<br>


while this second image is the district summary dataframe with the scores changed to Nans.
<br>
<br>
<img src="https://github.com/Bulzeye89/School_District_Analaysis/blob/main/Resources/Challenge%20District_summary_df.png">

<br>
<br>

The school summary saw similar miniscule changes that can be seen below.
<p float="left">
<img src="https://github.com/Bulzeye89/School_District_Analaysis/blob/main/Resources/Module%20per%20school%20summary%20df.png" width=40% height=50%>
<img src="https://github.com/Bulzeye89/School_District_Analaysis/blob/main/Resources/Challenge%20per%20school%20summary%20df.png" width=40% height=50%>
</p>

<br>
<br>

The results also slightly affected, by fractions of a percentage, the following:
- Math and reading scores for 9th grade
- Scores for medium school size when filtering by school size
- Scores for charter schols when filtering by school type 
<br>

In addition, when running the following code:
    
    '# Sort and show top five schools.
        top_schools = per_school_summary_df.sort_values(["% Overall Passing"], ascending=False)
        top_schools.head()

The removal of 461 9th grade Thomas High students' scores being changed to NaNs similarly resulted in fractional percentage differences, but Thomas High School still remained the 2nd school overall.  



## Summary: 
In an effort to uphold state testing standards in light of the evidence of academic dishonesty, only small fractional percentage changes were made that ultimately had no significant change to results of the data.  The school board can be advised that the 9th grade students from Thomas High School reading and math scores have been removed.  With the removal of the data, Thomas High still ranked second out of all the schools while other insights of the analysis held true and and virtually almost unchanged such as the district's overall scores, 9th grade overall scores, school sizes scores, and charter school scores.  In addition, I would like to note that while the scores of the 9th grade Thomas High students were changed to Nans, their count was not deducted from overall student count column as this would have affected other things suchs as per student budget.
