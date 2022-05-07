 # Project_1 : Is Daylight Savings Time a Killer?

## Hypothesis
   
   Does participating in daylight savings time lead to Californians being seriously injured or dying?
    
     Some of the topics we will be exploring:  
     
       How does changing our clocks for Daylight Savings Time in the Spring and Fall effect California's accident rates 
       and severity of accident? 
            
       Is when Daylight Savings Time changes, Spring vs. Fall make a difference? 
       
       How does California numbers compare to Arizona? AZ was chosen as a control group due to it's non-participation in
       DST and it is the closest to CA's topography and weather. (There are only two states that do not participate in DST;
       They are Arizona and Hawaii.)
       
## Data Sources/Resources       
   
   Vehicle crash data was taken from https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents,
   this data is part of a countrywide (continuous United States) database traffic accident database 
   for the United States during 2016-2021. 
   
   Dates for start and stop times for DST for the United States were taken from https://kb.lathem.com/hc/en-us/articles/115005029348-Daylight-Saving-Time-Starting-And-Ending-Dates, please see the below chart.
   
   
 ## Dictionary
   
      
Attribute	| Description

ID | This is a unique identifier of the accident record.

Severity | Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic (i.e., short delay as a result of the accident) and 4 indicates a significant impact on traffic (i.e., long delay).

Start_Time | Shows start time of the accident in local time zone.

Start_Lat | Shows latitude in GPS coordinate of the start point.
Start_Lng | Shows longitude in GPS coordinate of the start point.
Description | Shows natural language description of the accident.
City | Shows the city in address field.
County | Shows the county in address field.
State | Shows the state in address field.
Zipcode | Shows the zipcode in address field.
Weather_Timestamp : Shows the time-stamp of weather observation record (in local time).
Temperature(F) : Shows the temperature (in Fahrenheit).
Wind_Chill(F) : Shows the wind chill (in Fahrenheit).
Humidity(%) : Shows the humidity (in percentage).
Pressure(in) : Shows the air pressure (in inches).
Visibility(mi) : Shows visibility (in miles).
Wind_Direction : Shows wind direction.
Wind_Speed(mph) : Shows wind speed (in miles per hour).
Precipitation(in) : Shows precipitation amount in inches, if there is any.
Weather_Condition : Shows the weather condition (rain, snow, thunderstorm, fog, etc.)
Crossing : A POI annotation which indicates presence of crossing in a nearby location.
Give_Way : A POI annotation which indicates presence of give_way in a nearby location.
Junction : A POI annotation which indicates presence of junction in a nearby location.
No_Exit : A POI annotation which indicates presence of no_exit in a nearby location.
Station : A POI annotation which indicates presence of station in a nearby location.
Stop : A POI annotation which indicates presence of stop in a nearby location.
Traffic_Calming : A POI annotation which indicates presence of traffic_calming in a nearby location.
Traffic_Signal : A POI annotation which indicates presence of traffic_signal in a nearby loction.
Sunrise_Sunset : Shows the period of day (i.e. day or night) based on sunrise/sunset.
Date : Shows date of occurance
Time : Shows time of occurance
Year : Shows year of occurance
Month : Shows number of month 
Day : Shows number of day
DST_Flag : Will show DST_off_PRE, DST_off_Post, DST_on_PRE, DST_on_Post
DST_on_PRE : Ten days prior to Spring DST
DST_on_Post : This is the day of the Spring DST change plus the nine days that follow
DST_off_PRE : Ten days prior to Fall DST
DST_off_POST : This is the day of the Fall DST change plus the nine days that follow
DST : Daylight Savings Time



## Statistical Conclusions

