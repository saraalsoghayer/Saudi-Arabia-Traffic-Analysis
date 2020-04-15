## Problem Statment:

Saudi Arabia has the highest road accident death toll in the world. Working with both datasets, we expect to find trends between the number of driving licenses and the number of traffic accidents per region. Investigating the data, we found a couple of questionable drops and peaks in both the number of driving licenses issued and the number of traffic accidents. The main observations are as follows: a) a decrease in the number of accidents in 2017, b) an unusual significant drop in the number of driving licenses issued in one of the years. After analyzing the data, we expect to justify the above observations.


## Executive Summary:

There is a questionable decrease in the number of accidents in 2017, and an unusual significant drop in the number of driving licenses issued in one of the years. After Analyzing the data, we found that there is a positive relationship between number of driving licenses issued and number of accidents. We also noticed that the drop of the number of driving licenses issued in 2015 might be caused by the launch of Uber in Saudi Arabia. The decrease of the number of traffic accidents in 2017 might have been caused by many factors; the increase of fuel prices to support 2030 vision, canceling the immediate driving license test, and the implementation of new traffic laws followed by penalties for violations.


## Datasets Description:

Driving Licenses This dataset contains Saudi Arabia Driving Licenses Issued By Administrative Area for 1993 - 2016. Data from General Authority for Statistics . Follow datasource.kapsarc.org for timely data to advance energy economics research.

Traffic Accidents and Casualties This dataset contains Saudi Arabia Traffic Accidents and Casualties by Region for 2016. Data from General Authority for Statistics. Follow datasource.kapsarc.org for timely data to advance energy economics research.

data dictionary:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**year**|*integer*|Traffic_Accidents|The year the traffic accidents have been reported.| 
|**x**|*float*|Traffic_Accidents|The X geographic cooedinate of the traffic accidents.|
|**y**|*float*|Traffic_Accidents|The y geographic coordinate of the traffic accidents.| 
|**region**|*String*|Traffic_Accidents|The region where the traffic accidents have been reported.| 
|**accidents**|*integer*|Traffic_Accidents|The number of accidents that has been reported.| 
|**dead**|*integer*|Traffic_Accidents|The number of dead passengers that has been reported.| 
|**injured**|*integer*|Traffic_Accidents|The numberof injured passengers that has been reported.| 
|**year**|*integer*|Driving_Licenses|The year the driving licenses have been issued.| 
|**region**|*String*|Driving_Licenses|The area where the driving licenses have been issued.| 
|**driving_licenses**|*Integer*|Driving_Licenses|The number of driving licenses that has been issued.| 
|**x**|*float*|Driving_Licenses|The X geographic cooedinate of the region.|
|**y**|*float*|Driving_Licenses|The y geographic coordinate of the region.| 

We merged the two datasets during the EDA part for easier analysis and named the dataset "inner_merge" that combines similar columns and no null values (only contain the common years 2017/2016)

We also created another dataset that combines similar columns and has null values(contains the years 1993-2017) as the driving licenses dataset has more historical information than the traffic accidents dataset.


## conclusions/recommendations:

- Riyadh, Eastern Province, and Makkah have the highest traffic accidents and driving licenses issued.
- There is a positive relationship between bumber of driving licenses issued and number of accidents.
- The drop of the number of driving licenses issued in 2015 is caused by the launch of Uber in Saudi Arabia.
- The number of traffic accidents in comparison to the number of driving licenses issued in 2017 dropped by almost 36% compared 2016. The followings might be the causes:

- The gap between number of driving licenses and traffic accidents might have been caused by the increase of fuel prices to support 2030 vision as it decreased the number of traffic accidents.
- The gap between number of driving licenses and traffic accidents might have been caused by canceling the immediate driving license test as it decreased the number of traffic accidents.
- The decrease of the number of traffic accidents might have been caused by the implementation of new traffic laws followed by penalties for violations.

For further investigation into the case, Future years of number of accidents/driving licenses would be beneficial to further support my claims.
