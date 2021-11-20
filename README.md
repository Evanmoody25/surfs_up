# surfs_up

# Deliverable 1 

Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

# Deliverable 2

Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

# Deliverable 3

For this part of the Challenge, write a report that describes the key differences in weather between June and December and two recommendations for further analysis.

# Deliverable 1: June (summary statisticis)

![Deliverable1summarystatistics](https://user-images.githubusercontent.com/89880015/142737316-d731d7b4-3f56-4bf6-8015-ca712f935242.PNG)

# Deliverable 2: December (summary statistics)

![Deliverables2summarystatistics](https://user-images.githubusercontent.com/89880015/142737358-468b9079-68d7-4455-84cc-1f211aa4aab9.PNG)

# Deliverable 3: analysis and report

# Purpose

To retrieve more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

# Overview of the analysis: 

Using Python, Pandas functions and methods, and SQLAlchemy, we’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. We'll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics. Once our dataframe is created we are able to get our summary statistics by using the df.describe() code and method.

# Results

In the spots above, deliberables 1 and 2 have the summary statistics for the months of June and December.

# 1: 

The main point I have to make is that there is very little differentiation between the two months. The relatively stable climate, at least in my mind, is a hint towards relatively stable buisness. I compare this data to another beach town, Virginia Beach. There we see temperatures upwards of 90 in the summer months but frigid temperatures in the the winter which I imagine may hinder the buisness of the many surf shops in that area. 

# 2: 

Furthermore, the weather does not get too hot. June has a maximum temperature of 85 and December has a maximum temperature of 83. The heat may be just as efficient at driving away buisness as the cold. 

# 3: 

The interquartile range is also promissing as it suggests temperatures in the high 60s to mid 70s. 

# Two new quieries that we can make into the data

The first would have to be rainfall, somthing that we looked into within the module. I imagine rain has the ability to affect our buisness given we are focusing on surfing gear and ice cream. The next thing we should look into is UV rays. The sun can be especially damaging to certain individuals and should be taken into attention. News focus on the ozone layer in recent history has shown thaat although the ozone layer is healing, severe damage was done. 
