# bikesharing

## Overview of the analysis
The purpose of this challenge is to analyze a selected period of Citibike rental record, to look for possible relations between users and bike trips, and to visualize these possible relations. 
 
### Resource:
Source data are downloaded from [Citi Bike Link](https://ride.citibikenyc.com/system-data). File contains Citibike rental records of August, 2019, New York City.  
### Tool:
Tableau


## Results
  Key outcomes as shown in Tableau Story [link to dashboard](https://public.tableau.com/app/profile/kayla1042/viz/Challenge14NYCBikesharingStory/NYCStory?publish=yes) :  
###### image 1: Briefing
![briefing](https://github.com/kaylaisnomyname/bikesharing/blob/main/images/briefing.png?raw=true)  
1.There are total 2,344,224 trips recorded. Among these records, about 1.5 million trips are male users, about 588 thousand female users, and about 225 thousand users are gender-unspecified. 1.9 million users are annual subscribers, while the rest are pass-based customers. As per usages by gender (per weekday per hour) it shows most trips are on Thursdays by male users. Breakdowns are shown in the following images.  

###### image 2:  
![usage per weekday & per hour](https://github.com/kaylaisnomyname/bikesharing/blob/main/images/brief%20usages%20per%20weekday%20per%20hour.png?raw=true)  
2. The chart at the top is usages per weekday, filtered by user types and genders. Overall, Thursday is the busiest day of the week, despite gender. For pass-based customers, the most trip days are in weekends. The chart at the bottom is usages per hour, filtered by subcriber and customer. Overall the busiest hours are 5pm, 6pm, and 8am respectively. For pass-based custormers, the busiest hours are from 1pm~6pm. 

###### image 3:  
![brief trip durations](https://github.com/kaylaisnomyname/bikesharing/blob/main/images/brief%20trip%20durations.png?raw=true)  
3. Image 3 is the trip durations for users by gender. Both shows that most trip durations are within one hour. Majority of the trips are within the first 30 minutes. 

###### image 4:  
![usages per weekday per hour](https://github.com/kaylaisnomyname/bikesharing/blob/main/images/usages%20per%20weekday%20per%20hour.png?raw=true)  
4. Image 4 breakdowns the usages per weekday per hour. Weekday 7am ~ 10am and 5pm ~ 8pm are the busiest hours. In contrast, weekends the busy hous are in the middle of the day. Saturday is busier than Sunday.

###### imgage 5:  
![usage per weekday per hour per gender](https://github.com/kaylaisnomyname/bikesharing/blob/main/images/usages%20per%20weekday%20per%20hour%20per%20gender.png?raw=true)  
5. Image 5 further breakdowns the usage by gender. Results are consistant with image 4 above. For users with un-specified gender, checkout times are mostly at mid-day on Saturdays and Sundays.

###### image 6:  
![bike utilization](https://github.com/kaylaisnomyname/bikesharing/blob/main/images/brief%20bike%20utilization.png?raw=true)  
6. Image 6 shows the bike utilization. There are total 13,983 bikes in services. The top chart indicates total trip durations per bike ID, while the bottom chart shows the checkout time per bike ID. Bike IDs at the left most side of the chart  have the most service time and thus require frequent maintenance. 

## Summary  
  
In short, among the 2.3 million records, 81% are annual subscribers, 19% are daily-pass or 3-day-pass customers. The overal usages that indicating weekday morning and afternoon rush hours imply that subscribers tend to commute to work/school by bike. While pass-based customers usages are more on the weekends between 11am~8pm which is reasonalbe time for visiting city attractions or sightseeing.  
According to the usages, bike maintenance could be scheduled at the less popular hours of the day, for incidence 1am ~ 5am.   

There are about 65% of male users, 25% female users, and the rest are unknown-gender users. Considering the Trips vs Age as shown in image 7 below, the majority counts of trips are in between early 20s to 65. It is possible that the bikes are in one size, which is more fit for male users and middle age adults. It would be nice to have bikes in smaller sizes that could fit better for smaller figure body, or female or younger users. 

Possible further analysis : 
- Trips vs age  [link to image 7](https://public.tableau.com/app/profile/kayla1042/viz/Challenge14Overalltripsvsage/tripsvsage?publish=yes)  
###### image 7  
![per age 1](https://github.com/kaylaisnomyname/bikesharing/blob/main/images/trip%20vs%20ages.png?raw=true)  


- Trips vs location
###### image 8  
![per age 2](https://github.com/kaylaisnomyname/bikesharing/blob/main/images/trips%20vs%20location.png?raw=true)  
Image 8 shows the end location of the trips. Brown color circles are smaller counts of trips, darker blue circles indicate more counts of trips. As shown in the image, the darker blue spots are closed to major stations, such as the Grand Central Terminal, and schools, such as Stuyvesant High School. It could be a practical good idea to set bikesharing stations near major metro stations. 







